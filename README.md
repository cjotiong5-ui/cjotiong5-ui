<div align="center">

<img src="./img/github-header-banner.svg" alt="Cristan Jay Otiong — Computer Engineering Student and Software Developer" width="100%" />

[![Email](https://img.shields.io/badge/Email-you%40example.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:cristanotiong064@gmail.com)

</div>

---

##  About

- Building **ESOES CampusFlow**, an online enrollment system for the engineering programs of the Philippine College of Science and Technology (PhilCST) — students on one side, the Registrar on the other.
- Building it end to end: Flask API, SQLite schema and migrations, a vanilla-JS student portal, OAuth 2.1 + JWT auth, and a manual PythonAnywhere deployment.
-  Computer Engineering student at PhilCST.
-  I care about systems that stay correct under real pressure: seat-capacity races, duplicate enrollments, half-finished imports.
-  From Aguilar, Pangasinan.

---

##  Selected Work

<table>
<tr>
<td valign="top">

###  ESOES CampusFlow
<sub><em>Online enrollment system · Student portal + Registrar console</em></sub>

Replaces the paper enrollment queue for five engineering programs. A student verifies their email, picks a block section that matches their curriculum, reviews every subject and unit, and submits — or gets routed to the Registrar if they are irregular. The Registrar builds sections and timetables, imports whole class lists, and approves or returns each request with a note.

**What it does**

- Three-step enrollment wizard: profile → section → review
- Email OTP verification, forced first-password change, self-service reset
- Curriculum, grades and units-progress view per student
- Printable receipt snapshots of every past term
- Waitlist, schedule exceptions, re-enrollment clearance
- Installable PWA: offline page, campus map, light/dark themes

**Engineering behind it**

- OAuth 2.1 authorization-code + PKCE, ES256 JWTs, rotating refresh tokens
- Seat capacity enforced in a single transaction — no double-booking
- Spreadsheet import with a validation preview before anything is written
- Origin-checked state-changing requests, rate limiting, role guards
- Additive, backfilled SQLite migrations; no data-dropping steps
- 60+ automated test suites, each against its own temp database

<sub>Flask 3.1 · Python 3.11 · SQLite · JavaScript (ES2022) · PWA · openpyxl · PythonAnywhere</sub>

<sub><a href="https://esoes1.pythonanywhere.com">Live demo</a> · <a href="https://github.com/cjotiong5-ui/ESOES">Source</a></sub>

</td>
</tr>
</table>

<sub>More of my work is in the repositories below ↓</sub>

---

##  Stack

<sub><strong>Frontend</strong></sub><br>
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript_ES2022-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PWA](https://img.shields.io/badge/PWA_Service_Worker-5A0FC8?style=flat-square&logo=pwa&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive_Mobile_First-0A66C2?style=flat-square&logo=googlechrome&logoColor=white)

<sub><strong>Backend</strong></sub><br>
![Python](https://img.shields.io/badge/Python_3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask_3.1-000000?style=flat-square&logo=flask&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![openpyxl](https://img.shields.io/badge/openpyxl-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

<sub><strong>Auth &amp; security</strong></sub><br>
![OAuth](https://img.shields.io/badge/OAuth_2.1_+_PKCE-3C4F76?style=flat-square&logo=auth0&logoColor=white)
![JWT](https://img.shields.io/badge/JWT_ES256-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![RBAC](https://img.shields.io/badge/Role_Guards-B32D2D?style=flat-square&logo=shield&logoColor=white)
![Rate Limit](https://img.shields.io/badge/Rate_Limiting-525252?style=flat-square&logo=traefikproxy&logoColor=white)

<sub><strong>Tooling &amp; ops</strong></sub><br>
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Node](https://img.shields.io/badge/Node.js_Build_Step-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PythonAnywhere](https://img.shields.io/badge/PythonAnywhere-1E1E1E?style=flat-square&logo=pythonanywhere&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

##  GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=cjotiong5-ui&theme=shadow_blue&hide_border=true" alt="GitHub Streak" />
</p>

---

## 🎮 Play With Me

<details>
<summary><b>Pac-Man Contribution Graph</b></summary>
<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/cjotiong5-ui/cjotiong5-ui/pacman-output/pacman-contribution-graph.svg" alt="Pac-Man Contribution Graph" />
</p>
</details>

<details>
<summary><b>Contribution Snake</b></summary>
<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/cjotiong5-ui/cjotiong5-ui/snake-output/snake.svg" alt="GitHub Contribution Snake" />
</p>
</details>

---

<div align="center">
<sub>Built with Flask, SQLite and plain JavaScript — no framework, no ORM, no shortcuts.</sub>
</div>
