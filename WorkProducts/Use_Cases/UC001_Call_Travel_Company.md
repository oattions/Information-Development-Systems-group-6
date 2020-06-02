| Use Case ID                 	| UC001: Call Travel Company                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             	|
|-----------------------------	|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| User Story                  	| US201 As a Customer I would like my inbound calls' handling time to be reduced so my inquiries are resolved faster.<br>US202 As an Existing Customer I would like to be matched with an RM that has a deep understanding of the specific package or location I'm calling about so that my queries can be resolved faster.<br>US104As a relationship manager I want to be able to have inbound customers directed to an Interactive Voice Response Unit when lines are busy so that we can understand what a customer is looking for without spending resources on interacting with the customer.                                                                                                                                                                                                                       	|
| Goal                        	| To have an inquiry answered and to be served by a relationship manager.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                	|
| Priority                    	|  H                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     	|
| Actors                      	| Primary Actor – Existing Customer<br>Secondary Actor –  Relationship Manager                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           	|
| Pre-conditions              	| -The customer has access to a phone<br>-The CMC for the travel company is within its operating hours<br>-The CMC servers are working                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   	|
| Post-conditions             	| A call between a relationship manager and an existing customer has been successfully connected and is under way.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       	|
| Trigger                     	| Customer dials the travel company’s CMC number                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         	|
| Main Flow                   	| 1. If the line is busy, please refer to Alternate flow 1: “No Relationship Manager Available”<br><br>2. The customer is assigned a relationship manager which best matches their customer profile. See included use case UC002 : “Match Customer Profile with RM’s Skills” for more details.<br> <br>3. Relationship manager picks up the customer’s call<br>2. Relationship manager requests that the customer consents to some terms and conditions of the call, for example, the customer data may be collect to update or create a profile and that the call may be recorded. <br>Customer consents to the terms and services<br>4. Customer is served by a relationship manager for the duration of the call and states their inquiry. <br>5. The call concludes when the relationship manager hangs up the call. <br>6. Use case ends 	|
| Exceptions                  	| Exception 1 - The customer hangs up abruptly during any time<br>Exception 2 -At any time the Internet service cuts out for the CMC and the call ends abruptly <br>Exception 3 - Step 4 - 5 : Customer does not consent to terms and conditions of data collection.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     	|
| Includes/Extends/Inherits   	| Extends : UC009 : Speak to IVR<br>Includes UC002 : Match Customer Profile with RM’s Skills                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             	|
| Supporting Information      	| -The call must be recorded and stored in the database of the CMC for future training purposes <br>-The call must not be allowed to continue if the customer does not consent.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          	|
| Non-functional Requirements 	| Performance : <br>-The audio delay on the call must not be larger than 1 second. <br>Security:<br>-the contents of the phone call must be end to end encrypted.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        	|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    	|

                                                                                    	

| Alternate Flow 1    | “No relationship manager available.”                                                                                                                          |
|---------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Trigger**         | The line is busy, and no relationship manager is available at the time of dialing.                                                                 |
| **Step**            | 1. The customer is greeted by an interactive voice response unit (IVR) which asks the customer questions on why they are calling, and which package they are calling about, and finds a suitable RM to handle the customer. Please see Extended use case UC009: Speak to IVR for more details.<br><br>2. Customer is put on hold in a queue <br><br>4. Queue order is reprioritized according to customer scores (in a descending manner) every time a new customer enters the queue.<br><br> 5. Rejoin **main flow** at step 4. |
| **Post-conditions** | The call is picked up by a relationship manager.                                        |
| **Exceptions**      |Exception 1 - The customer hangs up at any time during step 1 - 2<br>Exception 2 - The IVR is offline.                                                                                                                                                   |