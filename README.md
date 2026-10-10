# Hi, I'm Jummy 👋

**Backend-heavy Software Engineer** · Python · Django · Celery · Redis · PostgreSQL · REST APIs
**Full-stack capable** · Next.js · React · Tailwind CSS
Author of *Django Through Stories* · Founder @ CodeHaven · Runs Lagos Tech Institute · Lagos, Nigeria 🇳🇬

I design and build backend systems: multi-tenant platforms, APIs, payment flows, background jobs and real-time features. I understand Django well enough to teach it, and I care about clean architecture, data isolation, tests, and software that keeps working after the demo. I can also take a product end to end: I build the frontend in Next.js, React and Tailwind CSS, so I can ship a complete feature from database to screen.

📫 **rafiuolajumoke7@gmail.com**

---

## 🔭 What I'm building

### Signal Watch — [`signal-watch`](https://github.com/Rafiu-Olajumoke01/signal-watch)
A backend intelligence system that watches public information sources, turns messy signals into structured events, detects meaningful change, connects related events, and alerts an organization when something important is emerging.

`Python` `Django` `Celery` `Redis` 

---

## 🏗️ Systems I've built

### Erudy (schoolHub): multi-tenant school management platform
One system serving many schools, with each school's data completely isolated from every other school's.
- **Tenant isolation:** every record carries a school, every queryset is scoped by it, and serializers reject cross-school references
- **Four roles** (Platform Owner, School Admin, Tutor, Student) with role-based permissions and token authentication
- **Enrollment pipeline:** public application → admin approval → payment → automatic student account creation and cohort assignment
- **Payments:** manual bank-transfer flow with promo codes, server-side amount calculation (the client never sets the price) and an admin review step
- **Academics:** class sessions, notes, assignments, capstone guidelines, bulk attendance, exams and results with score-integrity checks, certificates
- **Communications:** role-scoped announcements and threaded messaging
- 12 Django apps · Django REST Framework · Next.js frontend

### LASOP platform: production backend for a coding school
The live backend behind Lagos School of Programming, built with Django and a Next.js frontend.
- Student, tutor and admin dashboards with JWT auth
- Cohorts, class sessions and attendance tracking
- Bank-transfer payments with part-payment and promo codes
- Student project review pipeline: Under Review → Re-attempt → Approved, with tutor feedback and a public showcase
- Assessments, exams, results and certificates
- Real-time chat over WebSockets

### Chicken and Rice: food delivery platform
A food ordering and delivery website in live use by a real business.

---

## 📚 Teaching & writing

### *Django Through Stories* (publishing soon)
A book that teaches Django through stories instead of dry documentation, written for people learning backend development. Writing it forced me to explain every concept clearly, which makes me a better engineer and a better teammate.

### Lagos Tech Institute
I run Lagos Tech Institute, where I teach and mentor people learning to code.
📧 lagostechinstitute@gmail.com

---

## 🧰 Tech stack

**Backend:** Python · Django · Django REST Framework · Celery · Redis · WebSockets · JWT / token auth
**Data:** PostgreSQL · MariaDB/MySQL
**Infra & tooling:** Docker · GitHub Actions · Git · Linux · cPanel/Passenger deployments
**Frontend:** Next.js · React · JavaScript · Tailwind CSS · HTML5 · CSS3 · responsive, role-based dashboards

---

## 🧠 How I work

- Start with the data model and the failure cases, then write the endpoints
- Keep business rules on the server, never only in the UI
- Design for isolation and permissions from day one, not as an afterthought
- Small pull requests, clear commit messages, tests for the logic that matters
- Write down design decisions so the next engineer (or future me) knows why

---

## 🎓 Background

Trained at Lagos School of Programming, where I graduated as one of the top students, then went on to build the school's own production platform. Interned at Vault Software Company.

---

## 📊 GitHub

![Jummy's GitHub stats](https://github-readme-stats.vercel.app/api?username=Rafiu-Olajumoke01&show_icons=true&theme=dark&hide_border=true)
![GitHub streak](https://streak-stats.demolab.com/?user=Rafiu-Olajumoke01&theme=dark&hide_border=true)

---

## 🤝 Let's talk

Open to backend and full-stack roles, remote or Lagos-based.
Email me at **rafiuolajumoke7@gmail.com**.
