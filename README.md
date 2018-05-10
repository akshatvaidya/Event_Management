# Event_Management
This is an android app developed as a project in my CSE 5324 (Software Enginnering) class.

Here is the class project  - a campus  event catering system. Users (students and faculty)  can have events catered. Caterers are the people responsible for catering the event - this is typically a staff of 5-6 people. Caterer staff are workers helping with a catered event.
1.	Caterer - this user has the following functions
  a.	creates a catering event plan based on the users selected event 
  b.	adds resources to the event (food, drink, entertainment items etc)
  c.	schedules a place for the event
  d.	assigns staff members to each catering event
  e.	views calendar of catering events
  f.	views details of a specific event
  g.	deletes an event
  h.	update profile
  
2.	User
  a.	requests event - items, size of party, date, time, occasion type, duration
  b.	views schedule of events to determine availability which shows estimated prices based on selections
  c.	view reserved events
  d.	cancel reserved events
  e.	update profile

3.	Caterer staff
  a.	view events assigned
  b.	update profile
  
4.	Admin
  a.	review registration request
  b.	approve/reject registration request
  c.	edit user profile
  d.	delete caterer, user, or caterer staff

 Also have the standard functions like register, login, logout. Each system user must register and selects their role during registration - the admin reviews and approves selected roles. Assume that a single user that has multiple roles, e.g. User and Caterer would register twice with different ids. Each user registers with at least a user name, role, id, and personal details, contact information.
 
There are 5 Halls: A, B, C, D, and E. Capacities are 100, 25, 50, 25, and 75 respectively. The charge is $2/hour/capacity - A for a 3 hour event would be $600. The price is based on room capacity not people attending. Each halls cam only be reserved for 2-hours at a time minimum. Halls close at 11pm on week nights and 2am on weekends. They open at 7am each day except at noon on Sunday.

Food meal type: breakfast, lunch, supper. Meal cost: breakfast $8/person attending, lunch $12/person attending, and supper $18/person attending.

Food venue: American, Chinese, French, Greek, Indian, Italian, Japanese, Mexican, Pizza. The cost is the same for all.
Meal formality: informal or formal. Informal is no extra cost. Formal is 1.5 times the cost of the meal type and uses actual dinner ware, drink ware, tablecloths and linens. Informal is paper and plastic.

Drink venue: standard (non-alcoholic) and alcohol. Standard is no additional fee. Alcohol is $15/person attending.
A caterer cannot be assigned to more than one event at the same time. A caterer is assigned for the duration of an event.
The system does not deal with payment by users. Users will pay at the time of the event.
   


