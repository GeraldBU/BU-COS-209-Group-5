# Fix My Hall - PRD

### 1. Product Overview

Fix My Hall is a web platform for Babcock University students and staff to book school halls for events, and report problems in the hall (like broken AC, chairs, lights, projector) so maintenance can fix them fast.

Instead of going to the reception to register any problem the log book of the hall or to report fault, you do everything in one place.

### 2. Problem Statement
*What problem are we solving?*
Booking a hall is stressful. You don't know if hall is free, and sometimes two groups clash. Also, when something spoils in the  hall, it takes weeks to fix because nobody reports them properly and nobody follows up.

### 3. Business Objectives
*What does the website do?*
- Make hall booking easy and transparent
- Stop double-booking of halls
- Make hall faults get fixed faster
- Help school manage halls better and keep record of usage

### 4. Target Users
*Who will use the product?*
- *Students / Club Leaders:* To book hall for events and report faults
- *Staff / Lecturers:* To book hall for lectures, seminars
- *Hall Admin / Student Affairs:* To approve bookings and manage halls
- *Maintenance Team:* To see and fix reported faults

### 5 Research - Interviews
I asked a few people these questions: What was the last fault you had in your hostel? How did you report it? How long did it take to get fixed? What happened while you were waiting? What was the most annoying part of reporting it? If there was an app to report it, what would you want it to do?

Their responses were:

Person 1 - Aitan F. ... Her fault was no water and leaking tap. She told the porter and wrote it in the complaint book. It took about 4 days.

Person 2 - Osobe Temiloluwa, Samuel Akande SF01. His fault was leaking tap. He did not report it at all because he didn't know who to tell. Till now it has not been fixed. He said the app should let you take photo and write what the problem is.

Person 3 - Oshoke Emmanuel, Samuel Akande SF11. His fault was broken wall socket that stopped supplying power, and leaking bathroom tap. He walked down to porter's lodge and they wrote it in a physical logbook. It took about 4 days to fix. While waiting he had to go to extension cord to charge his phone and put bucket under tap to stop floor from flooding. What annoyed him most was having to go back repeatedly to follow up because there was no way to know if message had been passed to maintenance or when they were coming. He said the app should let students upload photo and show live status - Submitted - Assigned - In Progress - Fixed, send notification when technician is on the way, and let students rate or confirm repair before the matter is closed.

### 6. Proposed Solution
So the idea is to make a small web app. A student can open, pick their hostel and room, say what is broken, add a picture if they want, and submit. The manager will see it on their own page and change the status from submitted to in progress to fixed. The student can just check and see what is happening.

### 7. MVP
For now we are only doing the basics:
- Login / Signup
- Report fault with picture
- See my reports and their status
- Manager can see all reports and update status

We are not doing chat, payment, or anything extra for now. Just the main thing.

### 8. User Stories
- Student reports a fault from his room without going to the lodge.
- Student checks back to see if it has been fixed or is still pending.
- Manager opens the dashboard and sees all the new faults.
- Manager assigns it, marks it as in progress.
- Worker sees what he has to fix and marks it done.

### 9. Success Metrics
We will know it is working if:
- People actually use it to report instead of going to the lodge.
- Reporting takes less than 2 minutes.
- Most faults get fixed within 2 days.
- At least some students in the hostel try it in the first week.

## 10. Risks
- If it is too complicated, nobody will use it. So it will be very simple since nobody likes hard or lengthy things.
- If managers don't open it, reports will pile up. We need to remind them.
- Network is not always strong, so it should not be heavy.
- Some people might send fake reports for fun. Login should help reduce that.
### 11. Functional Requirements
*What must the system do?*
- Users must be able to sign up and log in
- Users must be able to view list of halls and their capacity
- Users must be able to check hall availability by date and time
- Users must be able to request / book a hall
- Admin must be able to approve or reject booking requests
- Users must be able to report a fault in a hall with picture and description
- Maintenance must be able to update fault status to "In Progress" or "Fixed"
- Users must be able to see status of their booking and fault report

### 12. Non-Functional Requirements
*How well must it operate?*
- Page must load in under 3 seconds
- Must work on phone and laptop
- Booking data must be accurate - no two bookings for same hall at same time
- Must be secure - only logged-in users can book
- Must be easy to use without tutorial
