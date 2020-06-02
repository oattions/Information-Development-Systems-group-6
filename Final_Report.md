# 1. Problem Definition
---
## 1.1 Problem Objectives

Through the Scrum Methodology, a team of developers will develop a Call Management Centre (CMC) system to facilitate an improved operation for a major travel company with dynamic flow control for their Relationship Managers (RM) and customers. This is achieved through multiple functionalities that will be defined through various Design Thinking approaches and finalized with User Cases and various UML diagrams such as:

* An algorithm and system to match customer profiles with an RM
* A user profiler tool
* IVR (Interactive Voice Response Unit)
* Automatically generate target list and script for potential customers

Ultimately, the product owner(s) (managers) will uncover multiple insights to suggest how their operations can be more productive to create value for customers and increase overall sales of holiday packages with the CMC system.   

The stakeholders of both the current and the new system are as follows : 

* The product owner (call center managers in this case)
* Existing and potential customers of the travel company 
* Relationship managers (both inbound and outbound)

# 2. Design Thinking
Through the use of design thinking principles such as empathy mapping techniques, we were able to create point of view statements which evolved into 'how might we' statements to address all potential pain points that users may have experienced with the existing system. These statements served as the basis for our user stories. 
---
### 2.1 How-Might-We(HMW) Statements

[See included files]

### 2.2 Design Thinking Reflective Statement
We assumed that the current CMC is inefficient as it matches customers with relationship managers based on availability rather than skills and expertise. 
We also assumed that the previous system had no scoring system, hence, did not prioritise customers with higher likelihoods of purchasing above customers who would otherwise never purchase. This would have been exacerbated by the fact that during busy times, customers were put on hold which would have prompted them to hang up and refrain from using the service again due to the long call handling time. 


Furthermore, it is also assumed that in both the pre-existing and newly proposed system that a customer could be calling the travel company's customer support line for reasons apart from holiday package enquiry. This raises the need for a customer to be redirected to a relationship manager from a call routing branch operator; The workload of whom will be drastically reduced by the proposed interactive voice unit in the new system. 


The process of designing the new system utilised 'Point of View' statements which allowed for the close examination of the perspectives of different users. These empathy statements allowed us to identify weaknesses in the existing system, and hence, facilitated the creation of How Might We (HMW) statements, which formed the basis of the User Stories which formed the foundation for the newer, more efficient system. 


An example of this process is as follows : 
> **POV:**  RM: “I wish I didn’t have to waste time calling customers who would’ve never bought a package anyway” 

> **HMW:**  How might we… Let Relationship Managers speak to fewer customers who are less likely to buy a package and more customers who are likely to buy a package. 

> **Resulting User Story:** As a relationship manager I would like customers to be filtered by how likely they are to buy a package so I can waste less time on customers who won’t purchase a package, and spend more time selling packages to customers who will. 

This example identifies that in the existing system, relationship managers spoke to all possible incoming customers instead of customers who had a higher likelihood of purchasing the product, which had resulted in longer, less productive call handling times, which would have greatly impacted the market share of the business.

# 3. Agile Methodology Used
The process of Design Thinking was firstly used to create assumptions of the existing system to understand the “Why”, “How” and “What” aspects of the travel company and its stakeholders of RMs and customers to understand their needs and solve problems of current inefficiencies of the existing system. Most importantly, the customer-centric approach was also used in the Design Thinking process to define the in-scope items. By journey mapping alongside the given scenario, we were able to brainstorm assumptions and test them to see the feasibility in meeting potential and existing client needs as well as maximising the productivity of RMs to improve overall operations and sales. Assumptions of the previous system which justify the need for a new improved system were based upon inbound calls, outbound calls and general. Empathy maps were applied for the following stakeholders: inbound relationship manager, outbound relationship manager, existing customer, potential customer and product owner. Point of View (POV) statements were formed to develop How Might We (HMW) statements which finally lead to User Stories that were then created into a Prioritised Backlog. 

After a defined scope, there were further feasibility testing for each sprint with the product backlog, estimates were calculated as well as Sprint Planning to forecast how much of the determined backlog will be developed during each sprint. This allowed the team to define the intention and hence the goal of the sprint. After this, the team designed how the product increment will be released and develops a work plan. The team decided upon three iterations with a ten-day sprint.

A project board was created with Google Docs to govern and depict the oversight responsibility for the work and ultimately ensure successful delivery of the project in a timely manner. In the latter part of Sprint Planning, the team collectively created a sprint backlog with items for the Sprints and plan for delivering product increment on Google Docs. This physical representation allowed the team to easily see their progress. 

With the use of Github as a means of version control and as a collaborative platform, the development iteration of the project was met using commit messages, pushing the deliverables in earlier iterations allowed tracking capabilities where the team members viewed and provided feedback for improvement. Moreover, a holistic overview of the completion status of the project is able to be seen via the use of git issues in tracking our product backlog. Issues are closed as commits complete the user story.

Stand-up meetings were held over Zoom every two days to assess progress and ensure that the deliverables of each iteration are going smoothly if the core team is acting efficiently and productively. As scrum assumes that plans need to be changed regularly, the frequent  Zoom meetings were timeboxed to 15 minutes (maximum 30 minutes) to communicate to each other how each member is progressing with their task, what is impeding their progress and their intentions between now and the next Scrum meeting. Once a Sprint has started only the Scrum Team can add or remove items in the Sprint backlog.

The scrum method allowed the team to emphasise accountability and teamwork. Major deliverables in the sprints included models where the core members had to significantly contribute to agree upon completion. Through the well-defined goals of the prioritised backlog after design thinking, the team had a common understanding of the time constraint to focus on delivering value for every iteration and utilised the importance to teamwork to repeatedly check and ask for feedback. When each deliverable was directed, trust was placed upon the team to get the iterations completed in time. With the Scrum Master (Angela) dedicating the deliverables to match the skill set of each member in consideration of our experience, strengths and weaknesses. This optimised the team’s productivity and flexibility allowing the trusting team member to approach and perform the task to their best ability. 

The meetings gave awareness and discussions on projects, the team also addressed potential changing business and technology needs and assessed whether it would impact the project. Zoom allowed each team member to share their screen into the progress of their deliverable and hence, each team member was able to cooperate and provide appropriate feedback. Frequent communication took place over Facebook also. As the Scrum Master, Angela was able to further direct the development team by overseeing and removing impediments (for example, define the assumptions to determine in-scope and out-scope items) to assist the Scrum Team in achieving its goals. There was a common understanding that the Development Team is collectively responsible for their work and performance as there is no defined hierarchy where no one has the authority to direct the team outside the rules set by Scrum. 

Each print would end with Sprint Review after the 8-9th day to examine every product increment that has been made in the sprint. By the 10th day, a Sprint Retrospective event was held to allow every member to reflect the working technique they have used and whether it optimised their productivity and how it could be improved for the next sprints. 

# 4. System Assumptions
All the assumptions made about the operational status of the existing system to justify the need for a new system. 

### 4.1 Inbound Calls
* All inbound calls were met with a human operator who asks questions about their parameters ( address, age, sex, etc) and which package they’re interested in before being redirected to an RM operator who will pitch the sale. <br>
* During busy times customers were put on hold and were not directed to an interactive voice response unit. <br>
* Previous inbound calls were not directed to specific RMs and were given to soonest available RM.<br>
### 4.2 Outbound Calls
* Customer profiles were not taken into account when fielding calls to RMs - customers were not segmented by profile. <br>
* Previously generated target lists do not take into account customer parameters before being given to an RM. <br>
* Previous outbound calls were not dialled automatically <br>
### 4.3 General 
* The old system only provided the original hiring questionnaire and did not adjust based on skills. <br>
* Skill profiles did not exist, so relationship managers could not be matched with their end customers based on knowledge.<br>
* Customers were not given points based on likelihood to purchase <br>
* RMs were not given a score based on performance <br>

# 5. Work Products
[Refer to the included /WorkProducts directory in the submission for this section]

# 6. Competitive Advantages 
### 6.1 General Competitive Advantages
With the Call Management Centre (CMC) system, operations for the travel company will be improved significantly due to dynamic flow control for inbound and outbound calls with a greater potential for relationship managers (RMs) to perform and advertise sales of holiday packages. The skill matcher feature for RMs and customers according to RMs skills and customer profile is a strategic tool to attain customer retention for existing customers to experience the best customer service to respond to their needs and become a trusted travel agent for all their future travels. This value of customer loyalty will further lead to word-of-mouth marketing for the travel company where the company can consider a discount in exchange for referrals. Also, the competitiveness of the travel agencies market is forcing its players to strategise and provide the best possible experience for the clients by inspiring trust as the foundation for every sale. The CMC system implements this value with the Profiler Tool and Skill feature to render the effect that the RMs have the clients’ best interest at heart to make convincing sales upon this trust. 
   

Hence, improved operations by specialisation through the CMC where customer service is improved by learning about the customer and assigning them to the right agent will build trust, foster goodwill and bring customer relations to the next level. 

Rating of the RM from a customer as another feature in the CMC system will be a valuable tool for the managers to evaluate the RMs and ensure that the best values, deals and customer services are provided to the clients. This data will also allow the managers to see the trends within the company which then can be compared to the industry or competitors to make further decisions and strategies to upgrade its operations. 

A score from 1-10 based on the likelihood to purchase the product is given to a customer according to some preloaded criteria at the automatic branch exchange will greatly optimise the company’s productivity. This score is dynamically updated following each customer interaction. A customer with a higher score will be prioritised and have their queue times expedited during busy periods. This will greatly reduce the time handling time spent on calls which do not yield sales. 

Implementation of the call routing and IVR (Interactive Voice Recorder) feature for inbound calls to further reduce operating costs for the company as it removes the need for a routing operator to reroute customers to appropriate RMs. It also provides a way for the customer to remain engaged in the system while being in the queue, hence reducing the likelihood of a customer hanging up before being served. The IVR will ask the customer about which specific package they may be inquiring about so that a more precise decision can be made on the RM to route them to. The aforementioned features of RMs scoring (profiling) and specialisation will allow managers to assess and spot inefficiencies with indications of their strengths and what needs to be improved where there may be opportunities to focus on RMs’ training and coaching. 

The automation of the manual tasks of RMs will minimise their busy time to a significant extent.  Therefore, this will improve agent productivity and customer satisfaction where per-call handling time is decreased where there will be more time allocated for outbound calls to reach potential customers and carry out more effective calls. 

### 6.2 Effect if Project Fails 
In contrast, if the CMC system fails, there will be inefficiencies for the company where the RMs’ expertise cannot be utilised to its maximum potential leading to the increase with customer’s hold time and thus, diminishing customer satisfaction. If the CMC system fails due to long system response time and low speed and poor telephone connectivity, corresponding problems where functions of scoring and profiling compromised will have detrimental impacts on the travel company. Managers will not be able to see the RMs score and hence, cannot analyse performance and define potential factors that could be improved on resulting in inconsistencies with the customer experience. Clients who deemed the experience as negative will not proceed with their purchases with the company, nor will they refer other potential customers to the company.  
