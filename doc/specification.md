Project Specification & Database Design

THE GUIDELINE OF THIS PROJECT ;

●	Requires PHP to process logic (e.g., user input, decision-making)
●	Uses MariaDB to read/write meaningful data
●	Produces dynamic content on the webpage



1. Demo Scenario Overview
<<<<<<< HEAD
●	A user fills out a booking form with their name, ID, phone number, and preferred time slot.
●	The system processes the input, assigns an available court, and saves the booking to the database.
●	A confirmation page displays the booking details.
●	An admin/demo page shows a list of all bookings.
=======
●	A user fills out a Amount($), Date, Category, Notes.
●	The system processes the input, saves it , and input into the booking to the database.
●	A save button displays in the log box.
●	An admin/demo page shows a list of all saved expenses.
>>>>>>> 1d0e4dd (Development progress check (Wed. of Week 16))


2. Planned URL Endpoints

<<<<<<< HEAD
URL Path	Method	HTTP Variables	Session Variables	Database Operations
/booking_form.php	GET	-	-	-
/submit_booking.php	POST	name, id, phone, timeslot	None	Insert booking, assign court, check time
/confirmation.php	GET	booking_id	None	Fetch booking by ID
/view_bookings.php	GET	-	None	Fetch all bookings
=======
public/

index.php
create.php
edit.php
delete.php
categories.php
summary.php

func/
db.php
>>>>>>> 1d0e4dd (Development progress check (Wed. of Week 16))
