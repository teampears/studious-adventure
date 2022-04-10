# Business need
The ongoing effects of the pandemic have created an increased need for support in our community, this is coupled with inflation that is particularly acute in its impact on non-discretionary items, food, rent, etc. have created demand growth that is leveling up. While the food bank has the logistic capacity to meet the need on the supply end the surge in demand has in many cases overwhelmed the organization’s capacity to book orders. Hight wait times and increasing call drops are presenting an increasing barrier to service.
The opportunity here is to design, prototype, and (likely later) explore the development of a solution that allows clients to book hamper 24/7. Thus, eliminating barriers to access and potentially freeing up time to grow the overall impact of the Food Bank on the lives of people facing food insecurity.

# Opportunity
The Regina Food Bank uses a Customer Relationship Management (CRM) tool for food provisioning built by a company called Link2Feed (L2F).  L2F has signed an exclusive engagement with Food Banks Canada to manage CRM activities. At the beginning of the pandemic, L2F rushed a product to launch that allowed for online scheduling, where the Regina Food Bank was part of the pilot group. Ultimately the project failed because its application was better suited to real-time sign up (i.e. when clients were already inline) and was not a viable solution for advanced booking.

The system provisioned by L2F can import and export data and can integrate through an application programming interface (API). The opportunity here is to design, prototype, and (likely later) explore the development of a solution that allows clients to book hamper pick-ups 24/7. Thus, eliminating barriers to access and potentially freeing up time to grow the overall impact of the Food Bank on the lives of people facing food insecurity.

## Challenge
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
In the first pahse of the project, when we were first introduced to the probelm and opportunity we decided that the episodic clients, who may be new to seeking assistance from a service such as the Food Bank, would be the northstar client for this project. As these folks may not be familiar with the process, it is important to reduce the severity of the barriers (onboarding) to them as much as possible. And the carryover client would include chronic clients who require more regular assistance. As these clients are already familiar with the physical process of booking. They will now benefit from simpler and more easy to manage bookings.
During this project number of assumptions were made. For instance, we assumed that the Regina Food Bank (RFB) has only two major types of clients, episodic and chronic clients. This assumption somehow made things little eaiser and helped us focusing on the requirments and needs of these two groups of clients. 

# Clients or Customers

### Northstar
The northstar client is episodic users who are new to having food insecurities. The amount of clients the foodbank has had to serve has increased significantly due to the pandemic, and inflation - new clients are not familiar with the platform and have been putting increasing strain on the phone booking lines.

### Carryover
Chronic clients who are already onboarded and are familiar with the proccess of booking will appreciate the extra ease to book hampers, though these users would be familiar with the previous method of booking. Agencies such as Salvation Army requiring bulk booking would also be included in carryover customers. Web based booking tightly coupled to the Regina Food Bank's CRM will allow for increased ease of booking.

## Assumptions
The site will be developed, deployed, and managed using WordPress as a Content Management System.A minimum viable product will be delivered at the end of this project, more so following the form of an exploration of feasibility study. From this a fully featured product may be developed and deployed in a future opportunity.

## Constraints
* WordPress as the Content Management System
* Link2Feed as the CRM
* Routific handles deliveries and routing
* Some information collected is only to be used for statistical analysis to aid in advocacy efforts
* Number of client types was restricted to 2 for the purpose of the MVP

## Summary of Mapping Activities
![User Journey](https://mermaid.ink/img/pako:eNqFkU9rwzAMxb-K8LljsLE_-NimO41ttNdcjK0kahIrKE6hlH732WmyMlg7n4zf7-lJ8lFZdqi02vEgHg-5BwgUGoTN2xI-fUMeYclcky-T1qMNxB4yLKKSXtL5Ei4oeqygSbKGBw2rStiTXcC6o54d2Zl-RyMeCmYH3CW81_Cof2FzzIrbzsglh2w9dPeZ0B7vQiWDhqcbQZP7HGUrJov96LgGBmoT8Xyl5tzVB5YcyISfvrbYROkyzX8FNmiRRniuML7s4wbZFyTttMWXG8PNjn7MPue-_smrhWox1iQX__mY_LkKFbaYKx2vzkidq9yfIjd0Lo61dhRYlC5M0-NCmSHw9uCt0kEGnKGMTCmmnajTNyJLxE0)

## User Story Mapping

## Minimum Viable Product Selection

## Summary of Prototyping Activities

---
# Project Results
>> Headings for keypoints to be made, headings do not neccessarily have to stay in final report
## Likes / Dislikes
Disliked the idea that we are constrained to use WordPress, because it sometimes limited us, as mentioned later in this report. 
Liked the idea that we solved a real world problem and had a chance to meet with customer to get feedback which helps us see and learn what it looks like out in industry. 
liked that we were given enough time to plan for the prject which helped in speeding up the other phases of the project. Knowing what we are doing and how we are doing easies the next phases in the development this project. 
Liked that we were given the chance and time to implement high fidelity prototypes of our design idea. Thus, saving us time in the last pahse of this project, coding/implementation phase, because we knew what we are doing and the look of what we are doing. 
## What went well


## What didn't go well

## Prototype to WP success
Due to the fact that we did not use WordPress customize themes we were succefull in translating our hight fidelity prototypes to WordPress reality. we were able to use similar layout, images and colrs to the one we had in out prototypes which somehow made the WordPress experince easier and faster.  
## PCD influences in designs

## What should be done similarily in the future

## What should be done differently in the future

## Future opportunities and design ideas

---
# WordPress Development
**Key points:**
- Plugins were found to be problematic, majority of features behind paywalls
- Majority of scheduling plugins baked in CRM type functionality with minimal flexibility in regards to connecting to external CRM(Link2Feed)
- Longevity and support of plugins was questionable
  - Future inhouse support was mentioned, train on plug in developed rather than rely on a 2nd external supporter for soley plugin support
  - This allows for streamlining of support services
