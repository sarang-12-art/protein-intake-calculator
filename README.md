# protein-intake-calculator
As a beginner in programming, I recently built a simple web-based Protein Intake Calculator.
Initially, I built a web-page where:

🔹 Users can enter their weight, select foods & quantities
🔹 An HTML form sent this data to a C-based CGI backend
🔹 The C program calculated:

 1) Required daily protein
 2) Protein from selected foods
 3) Remaining amount

🌐 This was hosted locally using XAMPP, and shared online via Ngrok.
But the experience wasn’t as smooth as I expected , i faced some problems.

📌 So, I iterated the project by moving all the protein calculations to the browser using JavaScript​:
✅ Faster, real-time updates
✅ No need to compile C code or rely on CGI
✅ Fully client-side, mobile-friendly experience

🔄 Final Tech Stack:
Frontend: HTML + CSS + JavaScript
Backend (initial): C via CGI (GCC, XAMPP, Apache)
Hosting: XAMPP + Ngrok (for live testing)

💡 This shift taught me the value of flexibility in web tech, and how JavaScript can simplify interactivity.


