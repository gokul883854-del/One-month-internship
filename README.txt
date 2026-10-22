CLOUD BASED VOTING SYSTEM — REPORT CODE

Files
-----
index.html
    The HTML and JavaScript voting demo transcribed from the "CODE IMPLEMENTATION"
    section (pages 14–16) of GOKUL Report.pdf.

How to run
----------
1. Extract this ZIP file.
2. Open index.html in a modern web browser.
3. Enter any non-empty Voter ID and password, then click Login.
4. Select Candidate A, B, or C and click Submit Vote.
5. Click View Result to see the in-memory vote counts.

Important limitations
---------------------
This is the small browser-only demo shown in the report. It is not a production
cloud voting system:
- Login only checks that the fields are non-empty; it does not authenticate users.
- Votes are stored in JavaScript memory and reset when the page is reloaded.
- The "already voted" flag is only for the current browser page/session.
- This code does not implement OTP, encryption, a database, Node.js/Express,
  AWS hosting, administrator access, or secure election auditing.
- Do not use this demo for a real election.

The report describes Node.js/Express and cloud services in its project overview,
but the report's code implementation section contains only this HTML/JavaScript
demo; no backend or database source code is included in the report.
