# Relationship Managers 

## US01: 
As a relationship manager I would like the customer’s profile or desired holiday package to be matched to my skill profile before the call gets sent to me so I can answer their questions better.
**Estimate:** 
    5 Story Points
**Priority :** 
    Priority : H 
**Acceptance Criteria :**  
>* Customer's profile is matched to an appropriate Relationship Manager's skill profile by the system prior to the call going through.
>* RM profiles sorted based on their age, sex, cultural background, language proficiency, experiences and product knowledge
>* Customer profiles are sorted based on their age, sex, cultural background and address
>* Customer profiles are assigned mostly likely desired holiday locations and most likely desired price ranges based on profile sorting. 


## US02: 
As a relationship manager I would like customers to be filtered by how likely they are to buy a package so I can waste less time on customers who won’t purchase a package, and spend more time selling packages to customers who will. 
**Estimate:** 
     3 Story Points
**Priority :** 
    Priority : M 
**Acceptance Criteria :**  
>* Customers are given a score of 1 - 10 indicating their likelihood to purchase the product based on preloaded criteria of : postcode, how many times they've previously purchased a package from the company, how many calls they've previously made (without purchasing a package) and other demographic parameters. 
>* Customers in an inbound call queue are prioritised based on score. Customers with higher scores will always be served before customers with lower scores. 
>* Customers in a targetted outbound call list are sorted in descending order by their score so that customers with a higher score are called first. 

## US03: 
As a relationship manager I would like a system that automatically dials the next customer on my target list so I can waste less time manually inputting a number and dialing it.
**Estimate:** 
    1 Story Points
**Priority :** 
    Priority : L 
**Acceptance Criteria :**  
>* When a relationship manager logs in the system that they are going to be making outbound calls, the system automatically dials their first target customer.
>* When a relationship manager finishes writing up notes for their outbound call and clicks confirm, the system automatically dials the next customer. 

## US04: 
As a relationship manager I would like to be provided with a specialised script to match a customer’s profile so I can know exactly what to say for each customer  
**Estimate:** 
    2 Story Points
**Priority :** 
    Priority : L 
**Acceptance Criteria :**  
>* Customer profiles are sorted based on their demographic parameters 
>* A script template is chosen depending on which demographic a customer profile is sorted into 
>* The template is automatically filled based on the customer's parameters and shown to the relationship manager when the call is received. 


## US05:
As a relationship manager, I would like to speak to customers who belong to similar demographics(age, gender, cultural backgrounds)  to me so I can communicate and relate with them better. 
**Estimate:** 
    3 Story Points
**Priority :** 
    Priority : M 
**Acceptance Criteria :**  
>* Customer's profile is matched to an appropriate Relationship Manager's profile by the system prior to the call going through.
>* RM profiles sorted based on their age, sex, cultural background, language proficiency, experiences and product knowledge
>* Customer profiles are sorted based on their age, sex, cultural background and address


## US06:
As a relationship manager, I would like to speak to and target to the right customers with outbound calls so I can be more effective at convincing due to my expertise in the holiday package/destination. 
**Estimate:** 
    4 Story Points
**Priority :** 
    Priority : H 
**Acceptance Criteria :**  
>* Customer profiles are sorted and matched with RM profiles based on their demographic parameters such as address, age, sex, cultural background, income bracket, etc. 
>* A unique target list of customers matching an RM's profile is generated for the RM prior to an outbound call shift. 

# Customers

## US07:
As a relationship manager, I would like to speak/target to the right customers with outbound calls so I can be more effective at convincing due to my expertise in the holiday package/destination. 
**Estimate:** 
    3 Story Points
**Priority :** 
    Priority : H 
**Acceptance Criteria :**  
>* Customer's profile is matched to an appropriate Relationship Manager's profile by the system prior to the call going through.
>* RM profiles sorted based on their age, sex, cultural background, language proficiency, experiences and product knowledge
>* Customer profiles are sorted based on their age, sex, cultural background and address

## US08:
As a cold called customer, I would like the subject matter of the call to be interesting to me so I can waste less time on a call that doesn’t concern me. 
**Estimate:** 
    2 Story Points
**Priority :** 
    Priority : M 
**Acceptance Criteria :**  
>* Customer profiles are matched with a relationship manager's profile so that all outbound calls are for customers the relationship manager can pitch to easily. 

## US09: 
As a customer, I would like to speak to Relationship Managers who have in-depth knowledge about the holiday package/s that I am interested in so that I am able to make an informed selection. 
**Estimate:** 
    2 Story Points
**Priority :** 
    Priority : H  
**Acceptance Criteria :**  
>* Customer's profile is matched to an appropriate Relationship Manager's profile by the system prior to the call going through.
>* RM profiles sorted based on their age, sex, cultural background, language proficiency, experiences and product knowledge
>* Customer profiles are sorted based on their age, sex, cultural background and address

## US10:
As a customer who had already made a purchase from this company before, I would like to be able to expedite my call wait times so I can buy my next package sooner. 
**Estimate:** 
    3 Story Points
**Priority :** 
    Priority : H  
**Acceptance Criteria :**  
>* Customers are given a score from 1 - 10 based on predetermined parameters like their demographic parameters (age, sex, location, etc.) and whether they've purchased packages before.
>* Customers with higher scores are prioritised and served first when inbound lines are fairly busy. 


# Product Owner

## US11:
As a product owner, I want the relationships manager’s profile change based on the results of their calls so that their profiles reflect their current knowledge and skills. 
**Estimate:** 
    5 Story Points
**Priority :** 
    Priority : M
**Acceptance Criteria :**  
>* Relationship Managers are given a score from 1 - 10 based on their performance following each call based on whether they made a sale, the call time, and the rating they receive from the customer. 
>* Relationship manager skills and knowledge are updated after every few weeks to reflect their knowledgebase and demographic more accurately. 

## US12: 
As a product owner, I would like to know what aspects are affecting sales numbers so I can adjust the business strategy accordingly
**Estimate:** 
    4 Story Points
**Priority :** 
    Priority : L
**Acceptance Criteria :**  
>* Customers are given a score from 1 - 10 based on their likelihood to purchase a package
>* Relationship Managers are given a score from 1 - 10 based on their performance following each call based on whether they made a sale, the call time, and the rating they receive from the customer. 
>* Scores of customers and employees are visible in the system. 

## US13:
As a product owner, I want  a score to tell me how productive a Relationship Manager is at their job so that I can provide them with longer or shorter call lists to make sure all targets are called in the shortest possible time.
**Estimate:** 
    3 Story Points
**Priority :** 
    Priority : M 
**Acceptance Criteria :**  
>* Relationship managers are given a score from 1 - 10 based on their skill level in handling customers
>* Relationship manager scores are adjusted after every call based on whether they made a sale, how long the call went for, and how the customer rated the experience following the call. 
>* relationship manager call lists are adjusted for length based on a relationship manager's skill level. 

# Call Routing Branch Operator 

## US14: 
As a call routing branch operator , I would like the customers to be greeted with an automated interactive voice system that lets them redirect themselves when lines are particularly busy so that I have a smaller workload. 
**Estimate:** 
    5 Story Points
**Priority :** 
    Priority : H 
**Acceptance Criteria :**  
>* When lines are particularly busy (when more than a certain amount of customers are on hold), an incoming call from a customer is greeted with an automatic interactive voice system.
>* Automatic interactive voice system determines whether the customer is calling to enquire about a holiday package or not 
>* Automatic interactive voice system asks customers questions to further build the customer's profile.
>* Automatic interactive voice system redirects customer to soonest available Relationship Manager without needing to pass through the routing branch operator. 