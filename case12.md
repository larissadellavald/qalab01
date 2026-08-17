Title:   Behavior when submitting the same booking twice in a row
Do this: Pick the date 05/09/2026, choose the time 20:30, set party size to 10,
         type the name "Frederico" and the email "fredericodellavald@gmail.com",
         then press Book.
         Press the browser/app back button to return to the booking form.
         Repeat the exact same steps — same date, time, party size, name,
         and email — and press Book again.
Expect:  Either a second booking is created (with a different reference
         number), or the second attempt is blocked.

Question for product owner: Does the system accept duplicate bookings
with the same data, or is there a check against it?