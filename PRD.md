 Campus Delivery Service (Babcock University)

Source of discovery: Campus Delivery Survey (Google Form, 11 questions)


1. Product Overview

Campus Delivery is a delivery service that picks up food and packages on campus and brings them straight to a student's hostel. Students can request and track deliveries without leaving their rooms. Deliveries are handled by verified dispatchers.

The service covers two kinds of orders:
Food orders: from the cafeteria and from non-cafeteria vendors.
Package pickups: from the campus drop-off point, delivered to the hostel.


2. Problem Statement

Students are expected to wear corporate attire before 5:00pm. On days without lectures, many do not want to dress up just to get a meal or collect a package. The survey was designed to measure how much this affects them.

Observed problem;

Students skip the cafeteria or food vendors before 5:00pm to avoid wearing corporate 
Dressing up for a simple errand is inconvenient on lecture-free days
Workarounds are unreliable: asking a friend, eating room provisions, or waiting until after 5:00pm 
The cafeteria requires an ID check-in, so a delivery service cannot simply buy a meal for someone 
Urgent packages are delayed or delivery windows are missed because the student cannot or will not leave the hostel 



3. Business Objectives


1. Give students a reliable way to get food and packages without breaking dress-code rules.
2. Create paid work for verified student dispatchers.
3. Build a sustainable revenue model (per-delivery fees, with a possible subscription).
4. Operate within school rules (corporate hours, cafeteria ID checks) so the service is approved and not shut down.



4. Target Users


User: Description: Main need 

Student customer: Resident student who orders food or packages, Get items without dressing corporate or leaving the hostel. 
Dispatcher: Verified student (or approved staff) who picks up and delivers, Receive clear orders, deliver, and get paid.
Admin / dispatcher manager: Runs the service day to day, Assign orders, verify dispatchers, handle disputes.

5. Stakeholders


Students (customers).
Student dispatchers: Q8 asks whether students are most comfortable with verified student dispatchers, official university-approved staff, or external riders.
University management / student affairs: approval of the service, hostel access rules, and enforcement of corporate hours.
Cafeteria management: needed if meal-plan or ID verification is to work digitally (Q5).
Food vendors: (fast food, shawarma, restaurants).
Hostel and security staff: access to hostel areas, especially for any external riders.
Project team:product owner, designers, frontend developers, backend developers, testers.


6. User Stories

Student customer

- As a student, I want to order food from my hostel so that I do not have to wear corporate attire for a simple errand.
- As a student, I want my cafeteria meal to be handled through my meal plan or ID so that I can use the cafeteria without going there.
- As a student, I want my package collected from the campus drop-off point and brought to my hostel so that I do not miss urgent deliveries.
- As a student, I want to see the delivery fee before I confirm so that I know what I am paying.
- As a student, I want to track my delivery so that I know when to expect it.
- As a student, I want to know my dispatcher is verified so that I feel safe.

Dispatcher

- As a dispatcher, I want to see available orders and accept one so that I can earn money.
- As a dispatcher, I want to mark an order as picked up and delivered so that the student and admin can see progress.

Admin

- As an admin, I want to verify and approve dispatchers so that only trusted people deliver.
- As an admin, I want to see all orders and their status so that I can resolve problems.


7. Functional Requirements


| ID (Requirement )

1.  The system shall let a student register and log in.
2. The system shall let a student create a delivery request (food order or package pickup) with hostel and room details. 
3. The system shall show the delivery fee before the student confirms an order.
4. The system shall support payment methods to be confirmed (see Open Questions). 
5. The system shall assign or offer each order to a verified dispatcher. 
6. The system shall let a dispatcher accept, pick up, and complete an order, updating its status each time. 
7. The system shall let a student track the status of an order (requested, accepted, picked up, delivered). 
8. The system shall support cafeteria orders through at least one agreed method: digital ID or meal-plan verification, or dispatcher-handled takeout. 
9. The system shall support package pickup from the campus drop-off point. 
10. The system shall let an admin verify, approve, and suspend dispatchers. 
11. The system shall store order history for students, dispatchers, and admins. 
12. The system shall notify students of status changes. 



8. Non-Functional Requirements


Area ( Requirement)

Security: Authenticated access; passwords hashed; role-based permissions (student, dispatcher, admin). 
Privacy: Student ID and hostel/room details are visible only to the people who need them for the delivery. 
Safety : Only verified dispatchers can accept orders. 
Performance: Order creation and status updates should respond quickly on typical campus mobile networks. 
Availability: Service should be available during the hours it operates, especially lunch and dinner periods. 
Usability:Simple enough to order in a few taps on a phone. 
Reliability: No order should be lost or silently dropped; every order ends as delivered or cancelled. 
Compliance: Must follow university rules on corporate hours, hostel access, and cafeteria ID checks. 


 9. Scope and Priorities


In scope (MVP, must have)

- Student registration and login.
- Create and track delivery orders.
- Dispatcher accept / pick up / deliver flow.
- Admin dispatcher verification.
- Delivery fee shown before confirming.
- One ordering channel (see Open Questions).

- Cafeteria integration (digital ID / meal-plan verification).
- Package pickup from the campus drop-off point.
- Notifications.

- Weekly or monthly subscription plan.
- Ratings and reviews for dispatchers.
- Multiple ordering channels.


10. Acceptance Criteria


Feature (Acceptance criteria)

Place an order: Given a logged-in student, when they submit a valid request with hostel and room, then the order is created and appears in their order list as "requested". 
Fee display: Given a student about to confirm, then the delivery fee is shown before confirmation. 
Dispatcher flow: Given a verified dispatcher, when they accept an order, then its status changes to "accepted" and the student sees it. 
Dispatcher restriction: Given an unverified dispatcher, then they cannot accept orders. 
Delivery completion: Given a picked-up order, when the dispatcher marks it delivered, then the status is "delivered" and it is stored in history. 
Tracking : Given an active order, the student can see its current status at any time. 
Admin verification : Given an admin, when they approve a dispatcher, then that dispatcher can start accepting orders. 

11. Assumptions and Open Questions


Assumptions

- Students have smartphones and data access in the hostels.
- The university will allow a delivery service to operate on campus.
- Enough students are willing to work as dispatchers.
- Survey results will be used to decide the final pricing and channel.

Open questions (each one is a survey question whose answers must be reviewed before the PRD is finalised)

Open question (Survey source) Decision needed 

1. How should cafeteria meals be handled: direct partnership with digital ID check, cash/transfer takeout through the dispatcher, or non-cafeteria vendors only? 
2. Who should deliver: verified student dispatchers, university-approved staff, or external riders? 
3. What price per delivery: ₦200–₦400, ₦400–₦600, ₦600–₦1,000, or a subscription? 
4. Which channel: mobile app or website, WhatsApp, or phone call / SMS? 
5. How many students would actually use it? 
6. How often do students order from outside today? 
7. What suggestions did students give about working within school rules? 


