This project is a Coders Lab© workshop. It's purpose is to make a reservation for a Conference Room, for the given day.
Assumptions:

Homepage:
* 1 reservation / day (for project simplicity)
* home page lists all conference rooms (with links to their detail view) with their status for the day.


Details view:
* after clicking on a room, you will see it's name, capacity and addition info (whether it's fitted with a projector)
* There are also options to make a reservation, delete or create a room or modify it

Edit view:
* User can add room info: name, capacity, projector availability

Reservation view:
* Shows room availability.


See overview of my project as of 16.10.2020 (almost fully functional but not fully styled) 
30 seconds no sound: https://youtu.be/XnK4BtwEjMA
3:30 minutes with commentary here (17.10.2020): https://youtu.be/DjPlpx1Vuuo

Project is being developed by Pawel Sarapata, student of Coders Lab Poland. It is based on Django framework and Python3.

UPDATES:
v1.00: 09.10.2020 - Initialized
v1.01: 10.10.2020 - Project renamed to "CR_Manager"
v1.02: 13.10.2020 - root view created ('/'), changes to base structure of the project
v1.03: 14.10.2020 - root view: fully functional
v1.04: 15.10.2020 - Added views: /room/new/, /rooms/, /room/delete/<id>/, /room/modify/<id>/, /room/reserve/<id>
		                  /room/detail/<id>/
v1.05: 16.10.2020 - Upgraded functionality, added style to /rooms/ 
v1.06: 17.10.2020 - Some optimization changes to views.py, finished styling (except for Reservation screen, which I will take care of tomorrow, added updated Project Overview
