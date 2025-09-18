<div>
<h1>Ethical Keystroke Capture — Demo & Project ✍️</h1>

<div>
<p>1) Save the demo Python file as keystroke_demo.py on your machine.</p>
<p>2) Run it with python keystroke_demo.py (requires Python 3 and tkinter).</p>
<p>3) Ask the subject to read and check the consent box before pressing Start Logging.</p>
<p>4) Everything typed inside the text area while logging is ON will be logged to keystroke_demo_log.csv with timestamps in UTC.</p>
</div>

<div>
<h1>Ethics Reminder ⚖️</h1>
<p>This demo ONLY captures keystrokes typed inside the demo application and requires explicit consent. Do not capture keystrokes from other applications or machines without explicit, lawful authorization.</p>
</div>

<div>
<h1>1) Safe demo app — keystroke_demo.py 🖥️</h1>
<p>Below is the safe demo application code.</p>
</div>

<div>
<h1>2) Project outline (README Structure) 📘</h1>
<p>- Title: Ethical Keystroke Capture — Demo, Analysis & Detection</p>
<p>- Abstract: Short summary of what you did, goals, and ethical safeguards.</p>
<p>- Objectives: Demonstrate keystroke capture, analyze typed data, discuss risks and detection.</p>
<p>- Ethics & Consent: Explain that demo only captures inside-app keystrokes and requires explicit consent.</p>
<p>- Implementation: Demo app (the tkinter code above), data format (CSV columns, timestamps), analysis scripts.</p>
<p>- Analysis: Aggregate typing rates (chars/sec), timing between keystrokes, basic keystroke dynamics.</p>
<p>- Detection & Mitigation: How defenders detect keyloggers and how to harden systems.</p>
<p>- Forensics: How to locate logs, how to prove consent, recommended evidence collection steps.</p>
<p>- Demo plan: Step-by-step script to run in interview.</p>
<p>- Conclusion & Future Work: Suggest network monitoring or ML-based detection.</p>
</div>

<div>
<h1>3) Analysis script (safe) 📊</h1>
<p>Use analyze_keystrokes.py to read the log and print basic stats (total keystrokes, speed, most common keys).</p>
</div>

<div>
<h1>4) Demo script for interview 🎤</h1>
<p>1) Intro: Explain consent and scope.</p>
<p>2) Show consent checkbox and Start Logging.</p>
<p>3) Type sample text; stop logging.</p>
<p>4) Open keystroke_demo_log.csv and show timestamps/keys.</p>
<p>5) Run analysis script to show typing speed and distribution.</p>
<p>6) Discuss detection & mitigation.</p>
</div>

<div>
<h1>5) Possible Interview Q&A ❓</h1>
<p>Q: Is this legal? A: Only with explicit consent. Otherwise, it’s illegal.</p>
<p>Q: How do attackers exfiltrate logs? A: Often via remote uploads or cloud-synced folders.</p>
<p>Q: How would you detect? A: Monitor for suspicious file writes, API hooking, or EDR alerts.</p>
<p>Q: How to mitigate? A: Use least privilege, whitelisting, EDR, and awareness training.</p>
</div>

<div>
<h1>README.md (for GitHub) 📄</h1>
<p>This repository contains a safe, ethical demonstration of keystroke capture intended for education and interviews. The demo only logs keystrokes inside the app with consent.</p>
</div>

<div>
<h1>License 📜</h1>
<p>Use this code for learning and demo purposes only. Always follow local laws and obtain explicit consent.</p>
</div>
</div>
