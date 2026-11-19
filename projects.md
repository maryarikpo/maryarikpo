[Home](index.md) | [Goals](goals.md) | [Skills](skills.md) | [Projects](projects.md) | [Experience](experience.md) | [Faith & Tech](faith-and-tech.md) | [Contact](contact.md)

# Projects

Each project below shows what I did, what was hard, how I worked through it, and what I learned, both professionally and spiritually.

---

## 1. Linux Deployment Proposal
**Course:** IT 210, Linux Fundamentals · **Role:** System administrator

### Context
I played the system administrator for PromisedLand.com, a fictional company with five call centers. Over seven weeks, I planned and built an Ubuntu server on AWS and wrote a deployment proposal covering setup, users and groups, storage, maintenance, networking, SSH, scheduled tasks, and firewall security.

### Challenges
I was completely new to Linux. Learning commands step by step was confusing, and I ran into errors connecting to the server and setting the right permissions.

### How I overcame them
I joined study groups, where classmates helped me understand what each command was doing. I practiced in the AWS lab every week, and by Week 5, I could use PowerShell to connect to the server and assign the right user and group permissions on my own. When errors came up, I read them carefully and fixed them one at a time.

### Results
I completed a full deployment proposal with a video demonstration of my working server, and Linux became my favorite course.

### Refined version (IT 497, November 2026)
After this course's ethics discussions, I reviewed my design again and made eight refinements. I asked three questions of every part: **What could go wrong? Who would be hurt? What is the simplest fix?**

| Area | Original | Refined | Why it matters ethically |
|---|---|---|---|
| Backups | 1 GB volume for 10 GB of data | 20 GB, root-only, monthly restore tests | Backups hold the same private data |
| Remote access | SSH keys only | SSH keys + MFA for admins | The safeguard missing at Change Healthcare |
| Data at rest | Not encrypted | EBS encryption with AWS KMS | Client and employee privacy |
| Reboots | Every two years | Monthly window, announced ahead | Security fixes are not delayed |
| Accounts | Expiry for temporary staff only | Same-day offboarding, quarterly reviews | No one keeps access they no longer need |
| Auditing | Admin actions logged | auditd on finance/CRM folders, fail2ban | Accountability, even for oversight access |
| Firewall | File-sharing port not named | Port 445 open only to the office network | Smallest possible exposure |
| Privacy policy | None | Retention rules and breach response plan | Honesty with clients and staff |

The biggest finding was a real error I missed the first time: the backup volume could never hold the data it was meant to protect.

📄 **[Read the full refined proposal (PDF)](linux-proposal-refined.pdf)**

### Lessons learned
- **Professional:** Hard skills become clear with steady practice, and asking for help is a strength, not a weakness.
- **Spiritual:** Setting permissions taught me that access is a trust. Luke 12:48 reminds me that "unto whomsoever much is given, of him shall be much required." The more access I have to a system, the more careful and honest I need to be.

---

## 2. SQL Database Coursework
**Course:** IT 143, Introduction to Databases · **Role:** Student developer in SQL Server Management Studio (SSMS)

### Context
I learned to create tables and write SQL queries using joins and set operations (UNION, INTERSECT, EXCEPT). I also built PivotTables, PivotCharts, and slicers in Excel and practiced interview-style SQL problems.

### Challenges
I was nervous about this course. There was a lot of code, SSMS often gave me errors, and I struggled to know which type of join to use and when.

### How I overcame them
I broke each query into small parts and tested them one piece at a time. I drew Venn diagrams to picture how each join combines data, and I kept practicing until the patterns made sense.

### Results
I can now query, combine, and organize data with confidence, which is a core skill for health data analysis.

### Lessons learned
- **Professional:** Big problems become manageable when I break them into small, testable steps.
- **Spiritual:** 2 Nephi 28:30 teaches that the Lord gives "line upon line, precept upon precept." I learned SQL the same way, and it gave me more patience with myself when learning feels slow.

---

## 3. Canvas Start Guide
**Course:** Technical Writing · **Role:** Technical writer

### Context
I wrote a step-by-step guide to help new students navigate the Canvas Student dashboard for the first time.

### Challenges
Writing for someone who has never seen a system before is harder than it sounds. I had to remember what it feels like to be new and avoid assuming the reader already knew anything.

### How I overcame them
I drew on my years at Springboard, where I explained processes to stressed students every day. I kept each step short, used plain language, and put the steps in the exact order a new student would follow.

### Results
I produced a clear, beginner-friendly guide, and the project greatly improved how I organize ideas and explain technical tasks.

### Lessons learned
- **Professional:** Good technical writing is about the reader, not the writer. Clear instructions save people time and stress.
- **Spiritual:** Matthew 25:40 reminds me to care for "the least of these." Helping someone who feels lost, even with a simple guide, is a small way to serve like the Savior.

---

## More projects

### History of Technology Podcast (HIST 175)
I researched, wrote, and hosted a podcast on medical technology, learning how discoveries like penicillin and anesthesia changed healthcare. It connected my health background with technology and strengthened my research and communication skills.

### Student Support at Springboard (Mentor and Advisor, 2022 to 2026)
I supported 80+ students per term remotely, helping those who were stressed or behind stay on track and reach their academic goals. I learned that listening first and responding with patience matters as much as the solution itself.

### Coming soon: IT 497 Capstone Project
A project connecting IT and health data, to be added by Week 6.
