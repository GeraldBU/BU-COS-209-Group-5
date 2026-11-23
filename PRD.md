# PRD.md - Hostel Fault Reporting System

## 1. Problem Statement
In our hostel, when something breaks, it's a problem to get it fixed. Like if your socket stops working or your tap is leaking, you have to go and find the porter and tell him. Sometimes he is not around, sometimes he forgets. And you don't know if anyone will even come. So the fault just stays there for days.

## 2. Users
The main people for this are:
- Students living in the hostel - we are the ones reporting.
- Porters / Hostel managers - they receive the reports.
- The maintenance guys - they are the ones who actually fix it.

## 3. How They Cope Today
What we do now is just go to the porter lodge and complain. Or we send a message on WhatsApp. Some people write it in a book at the lodge. But most times nothing happens because there is no record. You will complain today, complain again tomorrow, still nothing.

## 4. Research - Interviews
I asked a few people these qestions.
What was the last fault you had in your hostel?
How did you report it? 
How long did it take to get fixed? 
What happened while you were waiting?
What was the most annoying part of reporting it?
If there was an app to report it, what would you want it to do?

Their responses were

Person 1 - Abatan Fehintola, Sapphire Hall
Her fault was no water and dead light bulb. She told the porters and wrote it in the complaint book. It took 2 weeks. She said what annoyed her was the nonchalance and delay. She said the app should sort by category and call artisans automatically.

Person 2 - Osobe Temiloluwa, Samuel Akande SF01
His fault was leaking tap. SHe did not report it at all because she didn't know who to tell. Till now it has not been fixed. he said the app should let you take photo and write what the problem is.

Person 3 - Oshoke Emmanuel, Samuel Akande TF11
His fault was broken wall socket that stopped supplying power, and leaking bathroom tap. He walked down to porter's lodge and they wrote it in a physical logbook. It took about 4 days to fix. While waiting he had to use extension cord from his roommate's side to charge and put bucket under tap to stop floor from flooding. What annoyed him most was having to go back repeatedly to follow up because there was no way to know if message had been passed to maintenance or when they were coming. He said app should let students upload photo or video, show live status like Submitted -> Assigned -> In Progress -> Fixed, send notification when technician is on the way, and let students rate or confirm repair before the matter is closed.

## 5. Proposed Solution
So the idea is to make a small web app. A student can open it, pick their hostel and room, say what is broken, add a picture if they want, and submit. The manager will see it on his own page and change the status from submitted to in progress to fixed. The student can just check and see what is happening.

## 6. MVP
For now we are only doing the basics:
- Login / Signup
- Report fault with picture
- See my reports and their status
- Manager can see all reports and update status

We are not doing chat, payment, or anything extra for now. Just the main thing.

## 7. User Stories
- Student reports a fault from his room without going to the lodge.
- Student checks back to see if it has been fixed or is still pending.
- Manager opens the dashboard and sees all the new faults.
- Manager assigns it or marks it as in progress.
- Worker sees what he has to fix and marks it done after.

## 8. Success Metrics
We will know it is working if:
- People actually use it to report instead of going to the lodge.
- Reporting takes less than a minute.
- Most faults get fixed within 2 days.
- At least some students in the hostel try it in the first week.

## 9. Risks
- If it is too complicated, nobody will use it. So it will be very simple since nobody like hard or lengthy things.
- If managers don't open it, reports will pile up. We need to remind them.
- Network in hostel is not always good, so it should not be heavy.
- Some people might send fake reports for fun. Login should help reduce that.
