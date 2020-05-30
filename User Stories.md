## US101
As a **relationship manager** I want to be able to update the customer's profile so that I am able to make I am able to make generalizations of their pattern of purchases for future marketing/outbound calls

**Estimate:** 2 Story Points

**Priority:** M

**Acceptance Criteria:**

* A relationship manager is able to update a customer's profile during a call's wrap up.  

## US102 
As a **relationship manager** I want the customer's profile to be matched with packages they'll likely be interested in buying, so that I am better able to understand which packages I should be pitching to a customer

**Estimate:** 4 Story Points

**Priority:** M

**Acceptance Criteria:**

* holiday packages are assigned to a customer's 'relevant packages' list based on the customer's profile. 

## US103
As a **relationship manager** I would like to be able to have customers segmented by culture, location and other social demographic parameters so I know how to interact with them for an increase chance to achieve a sale or provide a service 

**Estimate:** 3 story Points

**Priority:** S

**Acceptance Criteria:**

* Demographic groups are assigned to customers based on their social, locational, and cultural demographics. 

## US104
As a **relationship manager** I want to be able to have inbound customers directed to an Interactive Voice Response Unit when lines are busy so that we can understand what a customer is looking for without spending resources on interacting with the customer. 

**Estimate:** 7 Story Points 

**Priority:** M 

**Acceptance Criteria:**

* When lines are busy, all inbound calls are redirected to an Interactive Voice Response Unit. 
* Interactive Voice Response Unit asks customer what package they're interested in and processes the information
* Interactive Voice Response Unit asks customer why they called, and processes the information.
* Interactive Voice Response Unit reroutes customer to next available RM that best matches the customer's profile and inquiry content. 

## US201
As a **Customer** I would like my inbound calls' handling time to be reduced so my inquiries are resolved faster. 

**Estimate:** 4 Story Points

**Priority:** S 

**Acceptance Criteria:**

* Average customer handling time is reduced 
* Customers calls and inquiries are fielded to an appropriate and knowledgeable RM 

## US202
As an **Existing Customer** I would like to be matched with an RM that has a deep understanding of the specific package or location I'm calling about so that my queries can be resolved faster. 

**Estimate:** 5 Story Points

**Priority:** M 

**Acceptance Criteria:**

* Holiday Packages that an RM is suitable to pitch can be added to an RM's profile. 
* The system automatically assigns holiday packages to RMs which have enough relevant skills and knowledge. 
* The system automatically routes a customer to RMs who are assigned 


## US203
As a **Potential Customer** I would like to be approached with relevant marketing material so I know that the service is not a scam and that I may consider purchasing the holiday packages

**Estimate:** 3 Story Points 

**Priority:** S 

**Acceptance Criteria:**

* Outbound customer target lists are generated based on RM skills knowledge. 
* The target list generated is in the form of a list of tuples of <potential customer, package proposed> 

## US204
As a **relationship manager** I would like to prioritise serving customers who have a higher likelihood to purchase score so that less time is spent serving customers who are less likely to yield sales. 

**Estimate:** 5 Story Points

**Priority:** M

**Acceptance Criteria:**

* Customers are given likelihood of purchase scores from 1 - 10 based on their region, demographic groups, and previous call and purchase history. 
* Customers with lower scores are served last when in a queue. 

## US205
As a **relationship manager** I would like to have a script generated from a customer's profile so that I can follow it when talking to the customer so that can be more personalised for a higher chance of making a sale.

**Estimate:** 3 Story points

**Priority:** C

**Acceptance Criteria:**

* A script which is personalised based on a customer's profile is generated for the RM to read when the call begins. 

## US301
As the **product owner** I want to be able to update RM profiles so that they can be sorted and matched with customer profiles and packages that are relevant.

**Estimate:** 2 Story Points

**Priority:** M 

**Acceptance Criteria:**

* relationship manager profiles are able to be updated to add new skills, knowledge, and demographic groups. 

## US302
As the **product owner** I want to have the RM's skill score be automatically updated following their calls, so that I can assess their performance and decide if further training or reward is required. 

**Estimate:** 4 Story Points

**Priority:** M

**Acceptance Criteria:**

* A skill score from 1 - 10 is calculated for an RM based on their average call handling time, and the ratio of their calls taken to sales made. 
* An RM's skill score is dynamically updated following every call they take. 

## US303
As a **product owner** I would like to have the system dial numbers automatically for the RM according to a customer target list so that the RMs are able to more efficiently make more calls to outbound customers in a shorter amount of time. 

**Estimate:** 1

**Priority:** C

**Acceptance Criteria:**

* After an outbound call is wrapped up, the system automatically dials the next customer on a target list. 

## US304
As a **product owner** I would like the system to determine the size of the targeted customer list for an RM's outbound calls based on their skill score so that more skilled RMs can serve more customers in a smaller amount of time. 

**Estimate:** 4 Story Points 

**Priority:** Should

**Acceptance Criteria:**

* A skill score from 1 - 10 is calculated for an RM based on their average call handling time, and the ratio of their calls taken to sales made. 
* A smaller target list is given to RMs with lower scores
* A larger target list is given to RMs with higher scores 


## US305
As a **product owner** I would like to have the system match customers based on RM performance and product knowledge

**Estimate:** 5 Story Points

**Priority:** M

**Acceptance Criteria:**

* Holiday Packages that an RM is suitable to pitch can be added to an RM's profile. 
* The system automatically assigns holiday packages to RMs which have enough relevant skills and knowledge. 
* The system automatically routes a customer to RMs who are assigned
* Customer calls are routed to and matched with RMs who have been assigned the same demographic groups as a customer, or have knowledge about packages relevant to a customer's demographic group.