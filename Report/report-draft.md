# Business need
The Regina Food Bank is the oldest food bank in Canada. The user base of the organization comes from all over the city and ranges from those who request services only once or twice to those who require services on an ongoing basis. The current system for an individual or family to request service is to phone in to a centralized call center and have a team member set up an appointment in our booking software.

Food insecurity alone is a daunting issue to tackle, while the Food Bank provides support to those in need additional barriers only hinder an individuals capacity to change their situation. As John put it, the goal of the Food Bank is to solve food insecurity, not to provide security and part of that solution is reducing the number and size of the barriers that folks suffering from food insecurity face.

The ongoing effects of the pandemic have created an increased need for support in our community, this is coupled with inflation that is particularly acute in its impact on non-discretionary items, food, rent, etc. have created demand growth that is leveling up. While the food bank has the logistic capacity to meet the need on the supply end the surge in demand has in many cases overwhelmed the organization’s capacity to book orders. Hight wait times and increasing call drops are presenting an increasing barrier to service.

# Opportunity
The Regina Food Bank uses a Customer Relationship Management (CRM) tool for food provisioning built by a company called Link2Feed (L2F). L2F has signed an exclusive engagement with Food Banks Canada to manage CRM activities. At the beginning of the pandemic, L2F rushed a product to launch that allowed for online scheduling, where the Regina Food Bank was part of the pilot group. Ultimately the project failed because its application was better suited to real-time sign up (i.e. when clients were already inline) and was not a viable solution for advanced booking.

The system provisioned by L2F can import and export data and can integrate through an application programming interface (API). The opportunity here is to design, prototype, and (likely later) explore the development of a solution that allows clients to book hamper pick-ups 24/7. Thus, eliminating barriers to access and potentially freeing up time to grow the overall impact of the Food Bank on the lives of people facing food insecurity.

# Challenge
A web based application tightly coupled to the Regina Foodbank's CRM will significantly improve the quality of service that the Regina Foodbank is able to provide and simplify statistical data collection for improved advocacy work.

One of the largest barriers is the capability to book a hamper, and to know with confidence that it will be available, without spending time on the phone waiting for help. Long wait times for phone booking has lead to an increase in the call drop rate as a high number of clients utilize pay-as-you-go phones with expensive by the minute usage.

# Stakeholders
## Internal
Project Sponsor - Dr. Tim Maciag

Team Pears Members - Ben, Daniil, Kawthar

## External
Customer Executive - John Bailey (CEO Regina Foodbank)

Clients - Community served by the Regina Foodbank

# High-level guidelines, principles, constraints, & assumptions
Provided by the Project Sponsor

**Design approach:** Design Thinking (Agile)/Fast Feedback Cycle

**License:** Creative Commons Share & Share Alike (CC BY-SA 4.0)

**Technology/Programming environment:** StoriesOnBoard, Adobe XD, WordPress, Local by Flywheel, GitHub

**Initial design guides**
- A clear and simple user interface with a focus on a design that works in low bandwidth environments
- Designed “guards” with respect to managing limits regarding the number of food hampers produced daily, e.g. real-time adjustments in total hampers booked would need to be guarded against overbooking
- System support will be provided by a third party. The Regina Food Bank does not have an in-house IT/IS team so any troubleshooting etc. will be done by an outside vendor

# Project Planning
## Clients
Some folks may not be familiar with the booking process, therefore it is important to reduce the severity of the barriers (onboarding) to access. Potential clients could include chronic clients who require more regular assistance, and episodic clients who may be more transient in their use. In both cases, some of these customers may already be familiar with the existing process of booking but stand to benefit from the simplicity and assurance a web based booking implementation would provide.

### Northstar
The northstar client is episodic users who are new to having food insecurities. The amount of clients the foodbank has had to serve has increased significantly due to the pandemic, and inflation - new clients are not familiar with the platform and have been putting increasing strain on the phone booking lines.

### Carryover
Chronic clients who are already onboarded and are familiar with the proccess of booking will appreciate the extra ease to book hampers, though these users would be familiar with the previous method of booking. Agencies such as Salvation Army requiring bulk booking would also be included in carryover customers. Web based booking tightly coupled to the Regina Food Bank's CRM will allow for increased ease of booking.

## Assumptions
The site will be developed, deployed, and managed using WordPress as a Content Management System. A minimum viable product will be delivered at the end of this project, more so following the form of an exploration of feasibility study. From this a fully featured product may be developed and deployed in a future opportunity.

## Constraints
* WordPress as the CMS
* Link2Feed as the CRM
* Routific handles deliveries and routing
* Some information collected is only to be used for statistical analysis to aid in advocacy efforts
* Number of client types was restricted to 2 for the purpose of the MVP

## Summary of Mapping Activities
The customer journey map shown below summarizes our findings from the [mapping activities](Mapping%20Activities/) previously completed. Affinity mapping built the basic structure of user needs, describing the actions of the user while empathy mapping envisioned the client's mindset and emotions as they step through the actions to use the service. Keypoints from both the affinity and empathy mapping activities where selected and set to a timeline to visualize the customers end to end experience. The customer journey map effectively allowed  the team to build a unified mental model of the experience to be shared with the RFB stakeholder to confirm that the vision was shared.
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
<!-- TODO maybe done !!-->
The website we produced is an MVP (Minimum Viable Product) because it has been developed with sufficeint features to satisfy our early users. Yet the final, full featured product to be produced after crucial feedback from the target audience/users which will help making the product even better in the next developemnt cycle.



## Summary of Prototyping Activities
The use double diamond model encouraged the team to ensure that the right problem was solved through the process of diverging and exploring multiple alternatives then converging on a solution.

The *divergence* phase took place with multiple [low-fidelity prototypes](Prototyping/Low%20Fidelity%20Prototypes/) to get a sense of the customer's needs and think openly about the problem by exploring multiple alternatives. In the *convergence* phase one [high-fidelity prototype](Prototyping/High%20Fidelity%20Prototype/) was created to narrow the focus of the ideas gained through alternatives explored during the low-fidelity prototype activity accompanied by feedback received from the RFB stakeholder.

In the calendar display, by enclosing the following two weeks of a selected date in a shaded area the gestalt principles helps to provide the user with additional information. Using the law of uniform connectedness, the shading within the calendar is a signifier of the days until their next booking could be placed, clearly communicating days in the near future that a new booking could not be placed within that time frame.

In the FAQ page similar questions are grouped together for continuity. The gestalt law of common region provides structure to help the user to understand the relationships which is further emphasized by ordering the questions chronologically in the order they may arise in the user's experience.

A focus was placed on minimizing extrenous design details to maintain useability in a low bandwidth environment. Under the assumption that most users would either be paying for low-capacity data mobile plans or using public wifi, a high bandwidth design with lots of graphics and resourse intensive plugins or scripting could be problematic.

---
# Project Results
<!-- Headings for keypoints to be made, headings do not neccessarily have to stay in final report -->
## Likes / Dislikes
<!-- TODO point form to elaborate on (added some points) -->
- Disliked the idea that we are constrained to use WordPress, because it sometimes limited us, as mentioned later in this report.
- Liked the idea that we solved a real world problem and had a chance to meet with customer to get feedback which helps us see and learn what it looks like out in industry.
- Liked that we were given enough time to plan for the project which helped in speeding up the other phases of the project. Knowing what we are doing and how are we doing it easies the next phases in the development this project.
- Liked that we were given the chance and time to implement high fidelity prototypes of our design idea. Thus, saving us time in the last pahse of this project, coding/implementation phase, because we knew what we are doing and the look of what we are doing.

## What went well
<!-- TODO  (maybe DONE) -->
The high fidelity prototypes designs went well and as expected, even though we had less time working on them we were able to produce interactive prototypes for desktop and mobile for our booking website.

The checkpoints with the RFB stakeholder provided the team with useful feedback and direction with regard to the progress made following each activity.

Since we developed the wp-theme from scratch we were able to replicate our initial hi-fi designs exactly.

## What didn't go well
More attention should have been paid to the Agile principles, namely; working software being the primary measure of progress; being able to maintain a constant pace indefinitely; technical excellence enhances agility; and maximizing the amount of work not done.

Managing the development through WordPress proved to be difficult as we did not have the tools we are accustomed to such as text editors and version control tools. This negatively impacted the efficiency of the development as finding and tracking changes all had to be done manually.

Furthermore, without proper codebases management, debugging fairly simple issues such as CSS conflicts took considerably more time than it should have. Some team members opted to work on changes locally rather than on the server. This added difficulty and considerable time in testing and left the remainder of the team lacking crucial details in regards to the state of the project and often left wondering when the work would be pushed. This approach did not allow for tasks to be done in parallel and increased the amount of re-work required to test for and resolve bugs.

The code from the building phase of the project was riddeled with tech debt. This is mainly due to no version control allowed changes to be managed properly or reviewed with the rest of the team. Also, since there was a lack of agile principles applied during development, the final phase ended up being rushed which lead the team to get a "as long as it works it's fine" dogma.

## Prototype to WP success
Due to the fact that we did not use WordPress custom themes we were succefull in translating our high fidelity prototypes to WordPress reality. We were able to use similar layout, images and colrs to the one we had in our prototypes which somehow made the WordPress experince easier and faster.

## PCD influences in designs
While planning, brainstorming and implementing this project, topics learnt in class have influenced our design and assisted in implementing an easy to use booking website. For instance, in class we emphasized on the importance of giving users an appropriate feedback of everything they do, so in our design we tried to give our users feedbacks and keep them informed of what they are doing. We tried to add signifiers when appropriate and we made use of Zeigarnik Effect and Postel's Law in order to make a more engaging experience.

## What should be done similarily in the future
<!-- TODO (more to add)-->
The initial design activities framing the problem and creating a visual picture for the team to get alligned on a proper solution was paramount to creating a consistant idea that was built upon throughout the project.


## What should be done differently in the future
Future projects should begin with a team alignment on expectations regarding team member's: roles, time allocated to complete the deliverables, expected delays due to busy times, and frequency of communication. Understanding of the logistic requirements to meet eachothers, and the clients expectations and the effective communication of blockers or delays is paramount to the success of a project. This alignment, done at regular intervals could have improved the productivity of the team and shifted from an individual focus to a team focus.

Testing with real users on the type of devices they would commonly use would have been beneficial, many other teams focused on desktop implementations while we focused on a mobile implementation and it would have been interesting to see the user test results from both. This would shift the focus from component reviews to experience reviews. Additionally, internal testing is time consuming and with the resources are team had proved to be daunting especially in the build phase. While the short demos during the stakeholder checkpoints provided some information, it was purely speculative as that information was not gained through testing of the actual prototypes.
<!-- TODO align on this (DONE) -->
As a team we think that the low fidelity prototypes were not as useful as the high fidelity prototypes. Thus, we think in future designs we would only use one which more likely will be the high fidelity prototypes. Throughout this project we refered back to hifis more than we did with the lofis, especially in the last phase of this project, coding phase. In the future it would be better if the lofi and hifi designs were done in parrellel allowing more time to be dedicated to the project building

## Future opportunities and design ideas
<!-- TODO point form to elaborate on -> (added some points) -->
To accompany the education piece on the Regina Foodbank, their efforts, and drive to help meet the dietary needs of the community that they serve, additional information from the Canada Food Guide could be added to the descriptions of each hamper. This information could help clients make an informed decision on their hamper selection.

To ensure the clients are satisfied with the service, a form of expectation management could be implemented by asking for feedback on the experience as well as whether the selection provided in the hampers met their expectations. Confirmation of pickup or delivery could be tracked in the CRM and connected to the status of previous bookings. This could allow for service side escalation of repetitive no-shows or failed delivery attempts.

Analytics on the most frequently submitted client questions could be tracked in the CRM to gain line of sight on potential repeat or high volume questions, triggering various actions. These actions could range from updating the FAQ to provide clients with an answer, to making UX changes in future iterations.

Agencies may find it helpful to set automatic orderplacing for a base number of clients, and additionally add additional orders if required by an influx of clients to their services. This would streamline their operation as well as it would reduce the management requirement to only changes in bookings, rather than the entirety of the bookings.

An AI chatbot may be added to provide users with information on frquently asked questions tying into the analytics of support previously mentioned.
---
# WordPress Development
The implementation of plugins and themes were found to be problematic, with the majority of features behind paywalls that disabled all but the most basic functionality. Scheduling plugins baked in CRM type functionality with minimal flexibility in regards to connecting to an external CRM. WordPress focuses on a framework for content creators and bloggers alike and the majority of these features are not applicable to a static site used for booking appointments.

As mentioned in the lessons learned, a lack of version control system made it difficult to track and manage changes especially through the development phase, and while these may not be as useful for a customer to update content on their site, it hindered our ability to rapidly iterate on changes through development.

A CD/CI pipeline would have also increased the speed of development and iteration by streamlining the deployment, rather than manually deploying changes and checking for conflicts.

Reliability and longevity of plugins was also questionable, when reading reviews as plugins were evaluated there was a common theme of plugins failing and having to rely on third party support supplied by the plugin creator. Since third-party support was initially required in the design guides, it did not make sense to have to rely on an additional party when the existing support contract could incorporate support for the custom plugin we've written. This allows for more direct and efficient control of the support, both logistically and contractually.

When relying on third party resources such as plugins, themes, and libraries, it is not uncommon to fall to the mercy of these creators, as these resources are updated they pose a high risk of introducing new bugs which could lead to the site not fuunctioning as it should at best, to crashing, and at worsed data loss. Compatibility issues may also be introduced, whether with other plugins or with the CRM.
