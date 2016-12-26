# EventPlannerSystem

The system we intend to discuss is called Event Planning System. This document contains a detailed project description of the system intended, data requirements and ER/EER Diagrams.

Purpose

The purpose of this prototype EVENT PLANNING SYSTEM is to cause the entire process to be more efficient and more effective, the net result of which is to plan and organize events efficiently. An Event Planning System generally involves multiple people, extremely large amounts of communication, and efficient planning and organization of events.

The Event Planning System supports the scheduling and operation of events. For the successful execution of the events, planning and scheduling must be done even months in advance sometimes. The facility and the date of the event are recorded on an event request. Additional actions are taken only if a request is approved and processes further. Each task is looked after by a manager.


Scope

The scope of the system is as follows - The Event Request forms the core part of the database. An event request represents an event scheduled at a facility. For example, we plan of conducting a baseball game in the college stadium. This event requires plans necessary for allocation of resources including personnel and equipment. The Event Task represents plans for the setup and operation of an event. Resources are used by each task. For example Stadium requires flood lights.

DATA REQUIREMENTS

Data requirements tell us what information we need from the database. Analyzing them, we can determine what subjects we need to store facts about (the tables) and what facts you need to store about each subject (the fields in the tables).

a) At the beginning, a Customer plans to conduct an event. So he may raise an event request to conduct the event. Each Customer has a unique Customer Number, Name, Address and Contact details.

b) Event Request need to keep track of event number, date held, date requested, customer number, the facility number, date authorized, status, estimated cost and estimated audience.

c) The Customer chooses various options that are required in the event.

d) Options include Music, Food, Decoration, etc., Options have unique Option ID and Price associated with them.

e) Music has different genres. Food can be chosen from different cuisines. Decoration styles include contemporary, historical etc.,

f) Each event task requires resources. Each Resource has unique Number, Name and Rate.

g) Each event is conducted in a Facility. Each facility has unique Number and Name associated with it.

h) Each Facility includes many amenities in them. The Amenities are identified by unique Numbers and they also have Names.

i) Tasks are organized at these amenities in the facility.

j) Each task is managed by an Employee. Each Employee has a unique Number, Name, Department, Phone and Email.


Assumptions

1) Each Event Task is managed by only one employee.

2) Each Event request upon approval is associated with one Event Task.

3) Price is fixed depending on the option.
