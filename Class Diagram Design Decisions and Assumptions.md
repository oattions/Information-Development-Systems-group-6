# Class Diagram Design Decisions and Assumptions

----
This document is meant to clarify any potentially confusing design choices. Therefore not all classes and relationships are mentioned. 

----
**Miscellaneous diagram convention related clarifications:** 

* Getters and setters are implied to exist for fields. 
* Similarly, boilerplate methods are not included. 
* Some attributes are assumed to be nullable. 


## Customer : 
**General Design Information:**

* A customer’s score is determined based on a calculation of the score of the demographics they belong to, the region they belong to, and the individual parameters of : the number of purchases they’ve made and number of calls they’ve made. 

**--Customer Relationships Explained--**


 **Demographic Group:** (can belong to one or many)


* A customer can belong to one or many demographic groups based on their parameters of age, sex, region, address, last name, etc. 
* A demographic group determines which holiday packages are relevant to them, and which skills a relationship manager must have to be relevant to serving this customer. 

## Relationship Manager:
**---Relationships Explained:---**


**Demographic Group:** (can be skilled at serving one or many) 

* RM is assigned demographic groups that they are good at serving. (this can either be assigned automatically based on the relationship manager’s profile, or manually by an administrator.)
 
**Holiday Package** (can be assigned to none or many): 

* RM Is assigned holiday packages that they are good at pitching and are knowledgeable about (this can either by assigned automatically based on the relationship manager’s profile, or manually by an administrator.)

**Skill:**(can have one or many) : 

* Is assigned to the relationship manager at profile initialisation when they filled out the questionnaire. 
* A relationship manager has a list of skills which are used to determine which demographic groups and holiday packages they’re automatically assigned. 
* Skills cannot be assigned automatically in the system, so an administrator is assumed to be able to assign an RM a new skill at any time. 


## Holiday Package :
**General Design Information**
 
* somebody manually adds packages and removes packages from the database. 
* Adding relevant demographic groups to a package means that RMs which specialise in the package will have calls from customers of that demographic redirected to them. 

## Call :
**An associative class between Relationship Manager and Customer** 

* The reason why it’s between the two interface classes is because every interaction between any kind of relationship manager and a customer will be a call in this system.

**General Design Information**


* It’s assumed that at the end of every call, the Customer’s score and the RMs score will be adjusted ever so slightly based on the call’s handling time, and whether a purchase was made during the call. 