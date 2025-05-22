# Memory Forensics: Autopsy vs Volatility (Visual Lab)

This project presents a **visual comparison** of two powerful memory forensics tools:  
**Autopsy** (GUI-based) vs **Volatility** (command-line based)

---

## 🔍 What This Lab Shows

- How each tool views memory dumps
- Which artifacts are easier to retrieve
- Practical screenshots from both tools
- Brief commentary on usability, depth, and features

---

## Screenshots & Highlights

### Case Setup in Autopsy
<img src="screenshots/01_autopsy-case.png" width="700"/>

> Autopsy’s case-based GUI allows step-by-step import of memory images.

---

### 🧵 Process Listing in Volatility
<img src="screenshots/02_volatility-pslist.png" width="700"/>

> Volatility's `pslist` command lists active processes at time of memory capture.

---

### 🧠 User Sessions Comparison
<img src="screenshots/03_user-session-autopsy.png" width="700"/>
<img src="screenshots/04_user-session-volatility.png" width="700"/>

> Volatility shows deeper memory session artifacts, while Autopsy focuses on file system remnants.

---

## 🧪 Tool Summary

| Feature              | Autopsy                         | Volatility                      |
|----------------------|----------------------------------|----------------------------------|
| Interface            | GUI                              | Command-line                    |
| Memory Plugin Depth  | 🔸 Basic                         | ✅ Advanced                     |
| Ideal For            | Beginners, disk forensics        | Malware, RAM analysis           |
| Custom Plugins       | ❌ Limited                       | ✅ Extensive                    |

---

## ✅ Verdict

Use **Volatility** for deep RAM analysis and malware triage.  
Use **Autopsy** for timeline reconstruction, carved files, and reporting.  
A hybrid workflow brings out the best of both.

---

## 👩🏽‍💻 Author

**Lydiah Muigwa**  
MSc Cybersecurity | Memory Forensics Enthusiast  
[GitHub](https://github.com/LydiahMuigwa)

---

## 🗂 Folder Structure

```text
memory-forensics-autopsy-vs-volatility/
├── screenshots/
└── README.md
