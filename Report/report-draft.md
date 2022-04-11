# Business need
The ongoing effects of the pandemic have created an increased need for support in our community, this is coupled with inflation that is particularly acute in its impact on non-discretionary items, food, rent, etc. have created demand growth that is leveling up. While the food bank has the logistic capacity to meet the need on the supply end the surge in demand has in many cases overwhelmed the organization’s capacity to book orders. Hight wait times and increasing call drops are presenting an increasing barrier to service.
The opportunity here is to design, prototype, and (likely later) explore the development of a solution that allows clients to book hamper 24/7. Thus, eliminating barriers to access and potentially freeing up time to grow the overall impact of the Food Bank on the lives of people facing food insecurity.

# Opportunity
The Regina Food Bank uses a Customer Relationship Management (CRM) tool for food provisioning built by a company called Link2Feed (L2F).  L2F has signed an exclusive engagement with Food Banks Canada to manage CRM activities. At the beginning of the pandemic, L2F rushed a product to launch that allowed for online scheduling, where the Regina Food Bank was part of the pilot group. Ultimately the project failed because its application was better suited to real-time sign up (i.e. when clients were already inline) and was not a viable solution for advanced booking.

The system provisioned by L2F can import and export data and can integrate through an application programming interface (API). The opportunity here is to design, prototype, and (likely later) explore the development of a solution that allows clients to book hamper pick-ups 24/7. Thus, eliminating barriers to access and potentially freeing up time to grow the overall impact of the Food Bank on the lives of people facing food insecurity.

# Challenge
A web based application tightly coupled to the Regina Foodbank's CRM will significantly improve the quality of service that the Regina Foodbank is able to provide and simplify statistical data collection for improved advocacy work.

Booking is not easy for clients. There is a need for clients to be able to book a hamper from anywhere at anytime with assurance that they will be able to get their hamper delivered. Long wait times for phone booking has lead to an increase in the call drop rate as a high number of clients utilize pay-as-you-go phones with expensive by the minute usage.

## High-level guidelines, principles, constraints, & assumptions
**Design approach:** Design Thinking (Agile)/Fast Feedback Cycle
**License:** Creative Commons Share & Share Alike (CC BY-SA 4.0)
**Technology/Programming environment:** StoriesOnBoard (Tim/Adam will be creating user accounts), Adobe XD, WordPress, Local by Flywheel, GitHub (public repository required)
**Initial design guides**
- A clear and simple user interface with a focus on a design that works in low bandwidth environments
- Designed “guards” with respect to managing limits regarding the number of food hampers produced daily, e.g. real-time adjustments in total hampers booked would need to be guarded against overbooking
- System support will be provided by a third party. The Regina Food Bank does not have an in-house IT/IS team so any troubleshooting etc. will be done by an outside vendor

# Project Planning
## Clients or Customers
### Northstar
The northstar client is episodic users who are new to having food insecurities. The amount of clients the foodbank has had to serve has increased significantly due to the pandemic, and inflation - new clients are not familiar with the platform and have been putting increasing strain on the phone booking lines.

### Carryover
Chronic clients who are already onboarded and are familiar with the proccess of booking will appreciate the extra ease to book hampers, though these users would be familiar with the previous method of booking. Agencies such as Salvation Army requiring bulk booking would also be included in carryover customers. Web based booking tightly coupled to the Regina Food Bank's CRM will allow for increased ease of booking.

## Assumptions
The site will be developed, deployed, and managed using WordPress as a Content Management System. A minimum viable product will be delivered at the end of this project, more so following the form of an exploration of feasibility study. From this a fully featured product may be developed and deployed in a future opportunity.

## Constraints
* WordPress as the Content Management System
* Link2Feed as the CRM
* Routific handles deliveries and routing
* Some information collected is only to be used for statistical analysis to aid in advocacy efforts
* Number of client types was restricted to 2 for the purpose of the MVP

## Summary of Mapping Activities
The customer journey map shown below summarizes our findings from the [mapping activities](Mapping%20Activities/) previously completed. Affinity mapping built the basic structure of user needs, describing the actions of the user while empathy mapping envisioned the client's mindset and emotions as they step through the actions to use the service. Keypoints from both the affinity and empathy mapping activies where selected and set to a timeline to visualize the customers end to end experience. The customer journey map effectively allowed  the team to build a unified mental model of the experience to be shared with the RFB stakeholder to confirm that the vision was shared.
<!-- journey
  title RFB Online Booking
  section Onboard
      Profile creation: 2: Chronic, Episodic
      Learn food options: 3: Episodic
  section Browse and Compare
      Login: 3: Chronic, Episodic
      Compare food choices: 5: Episodic
  section Availability
      Pickup/Drive-thru: 5: Chronic, Episodic
      Compare times: 6: Chronic, Episodic
  section Book
      Select options: 6: Chronic, Episodic
      Receive confirmation: 7: Chronic, Episodic
      Receive selections: 8: Chronic, Episodic -->

![User Journey](https://mermaid.ink/img/pako:eNqNkk1PwzAMhv-KlfMQEoiBcmMfnJBA27WXLHFX0zau3HSomvbfSbZ2CGkDcori580TW9kryw6VVh_cicc-8wCBQoWwepnBm6_II8yYS_LbVGvRBmIfKxs24tJRWu_COcWQFTSpruFOw7wQ9mQnsGyoZUd2pF_RiIec2QE3CW813Osf2OiZCX-2CMY7mHPdGMHzJbwlf8xd9QyJk8kWTBaj6eGy6XlnqDIbqij057bIll1zuxDa4U0opDum__QFqpNoegU99xbHOkbXWMXT73FMf9Gs0GJ8EFj2OUk9DPzxH4n2aDkZni7waqJqjDeSiz9in9KZCgXWmCkdt85ImanMHyLXNc4EXDoKLErnpmpxokwXeN17q3SQDkdoQWYrph6owxewv9FC)

## User Story Mapping
Building on the key actions from the affinity diagraming activities, these were expanded into user stories along with the associated user experience activities to define the minimimal viable product. The userstory map evolved over the course of the project lifecycle to capture ideas developed at the client checkpoints for additional features and future integrations, effectively building an end to end roadmap through MVPs and future opportunities.

## Minimum Viable Product Selection

## Summary of Prototyping Activities
The use double diamond model encouraged the team to ensure that the right problem was solved through the process of diverging and exploring multiple alternatives then converging on a solution.

The *divergence* phase took place with multiple [low-fidelity prototypes](Prototyping/Low%20Fidelity%20Prototypes/) to get a sense of the customer's needs and think openly about the problem by exploring multiple alternatives. In the *convergence* phase one [high-fidelity prototype](Prototyping/High%20Fidelity%20Prototype/) was created to narrow the focus of the ideas gained through alternatives explored during the low-fidelity prototype activity accompanied by feedback received from the RFB stakeholder.

In the calendar display, by enclosing the two-week allowable booking time frame in a shaded area the gestalt principles helps to provide the user with additional information. The shading within the calendar is a signifier of the days until their next booking could be placed, rather than being presented in a tabular form, providing the user with a familiar and comfortable interface.

---
# Project Results
<!-- Headings for keypoints to be made, headings do not neccessarily have to stay in final report -->
## Likes / Dislikes
- Disliked the idea that we are constrained to use WordPress, because it sometimes limited us, as mentioned later in this report.
- Liked the idea that we solved a real world problem and had a chance to meet with customer to get feedback which helps us see and learn what it looks like out in industry.
- Liked that we were given enough time to plan for the prject which helped in speeding up the other phases of the project. Knowing what we are doing and how we are doing easies the next phases in the development this project.
- Liked that we were given the chance and time to implement high fidelity prototypes of our design idea. Thus, saving us time in the last pahse of this project, coding/implementation phase, because we knew what we are doing and the look of what we are doing.
## What went well


## What didn't go well
Managing the development through WordPress proved to be difficult as we did not have the tools we as future software engineers are accustomed to such as text editors and version control tools. This negatively impacted the efficiency of the development as easily tracking and finding changes all had to be done manually.

Furthermore, without proper codebases management, debugging fairly simple issues such as CSS conflicts took considerably more time than it should have.

## Prototype to WP success
Due to the fact that we did not use WordPress custom themes we were succefull in translating our hight fidelity prototypes to WordPress reality. we were able to use similar layout, images and colrs to the one we had in out prototypes which somehow made the WordPress experince easier and faster.

## PCD influences in designs
The topics we learned about People-centered design helped us in implementing this design project. While planning, brainstorming and implementing this project, topics learnt in class have influenced our design and assisted in implementing an easy to use booking website. For instance, in class we empthesized on the importance of gibving users an appropriate feedback of everything they do, so in our design we tried to give our users feedbacks of what they do. we tried to add signifiers when appropriate to make the user experience more delightful.

## What should be done similarily in the future


## What should be done differently in the future
As a team we think that the low fidelity prototypes were not as useful as the high fidelity prototypes. Thus, we think in future that we would only use one of them when designing a software. As well, 

## Future opportunities and design ideas

---
# WordPress Development
**Key points:**
- Plugins were found to be problematic, majority of features behind paywalls
- Majority of scheduling plugins baked in CRM type functionality with minimal flexibility in regards to connecting to external CRM(Link2Feed)
- Longevity and support of plugins was questionable
  - Future inhouse support was mentioned, train on plug in developed rather than rely on a 2nd external supporter for soley plugin support
  - This allows for streamlining of support services
