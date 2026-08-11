<div align="center">

<img src="Open Graph Image copy.png" width="120" alt="ARC Logo"/>

# ARC INDUCTIONS 2026

### Automation & Robotics Club · BITS Pilani, Hyderabad Campus

<p>
<img src="https://img.shields.io/badge/Status-OPEN-00C853?style=for-the-badge&labelColor=0D1117"/>
<img src="https://img.shields.io/badge/Deadline-18_08_2026-FF5252?style=for-the-badge&labelColor=0D1117"/>
<img src="https://img.shields.io/badge/Trials-6-2196F3?style=for-the-badge&labelColor=0D1117"/>
<img src="https://img.shields.io/badge/Prior_Experience-NOT_REQUIRED-FFC107?style=for-the-badge&labelColor=0D1117"/>
</p>

<p><img src="https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
</p>

**The official tasks repository for ARC Inductions 2026**

Every "trial" below lives in its own repository with its own submission flow.
Pick what excites you. Break things. Ask questions. 

<a href="#-the-tasks"><img src="https://img.shields.io/badge/_JUMP_TO_TASKS-1F6FEB?style=for-the-badge"/></a>
<a href="#-how-to-submit"><img src="https://img.shields.io/badge/_HOW_TO_SUBMIT-238636?style=for-the-badge"/></a>
<a href="#-stuck"><img src="https://img.shields.io/badge/_GET_HELP-8957E5?style=for-the-badge"/></a>

</div>

---

##  Read This First

> **You do not need prior experience.** You need curiosity and the willingness to Google aggressively...

> All submissions happen through **Pull Requests**. If you've never opened one, that's fine.


> You may attempt **multiple tasks**. You are not expected to complete everything. A half-finished task with good documentation beats a complete copy-pasted one.

---

##  Prerequisite: Git & GitHub

<div align="center">

**Git** tracks every change you make to your code and lets you undo mistakes.
**GitHub** puts that code online so you can share it and collaborate.

*Every real robotics project is built by multiple people editing the same files — Git is the only reason that doesn't end in chaos.*

</div>

### 6 commands that cover 90% of your life

| Command | What it actually does |
|:---|:---|
| `git clone <url>` |  Download a repo onto your machine |
| `git status` |  Tell me what's going on *(use this constantly)* |
| `git add .` |  Stage the changes you want to save |
| `git commit -m "msg"` |  Save a snapshot of them locally |
| `git push` |  Upload your snapshots to GitHub |
| `git pull` |  Download everyone else's changes |

### Git mental model

```
your files  →  git add  →  git commit  →  local repo  →  git push  →  GitHub
```

<details>
<summary><b> Click here to actually learn it (do this before you start any task)</b></summary>

<br>

| Resource | Why | Time |
|:---|:---|:---|
| **[Learn Git Branching](https://learngitbranching.js.org/)** | Interactive and visual. The fastest way to *understand* branching. Do the Introduction Sequence, no need to do everything. | ~40 min |
| **[GitHub: Hello World](https://docs.github.com/en/get-started/quickstart/hello-world)** | Walks you through your first repo and your first PR | ~10 min |
| **[Oh Sh*t, Git!?!](https://ohshitgit.com/)** | This is for when you inevitably get lost and dont know how to restore your work... | The time when you mess shit up |
| **[Conventional Commits](https://www.conventionalcommits.org/)** | Write commit messages that don't say "added stuff", Just read up on "Conventional Commits" | ~5 min |

</details>

<details>
<summary><b> One-time setup (run these once, ever)</b></summary>

<br>

```bash
git config --global user.name "Your Name"
git config --global user.email "your.github.email@example.com"
```

Then set up SSH so you stop typing passwords:

```bash
ssh-keygen -t ed25519 -C "your.email@example.com"
cat ~/.ssh/id_ed25519.pub
```

Copy that output → GitHub → Settings → SSH and GPG keys → New SSH key

</details>

---

##  How to Submit

<div align="center">

```
FORK → CLONE → BRANCH → BUILD → COMMIT → PUSH → PULL REQUEST
```

</div>

<details open>
<summary><b>Step-by-step, with commands</b></summary>

<br>

**Fork the task repository** — hit the `Fork` button at the top right of the task's page. You now own a copy.

**Clone your fork**
```bash
git clone https://github.com/YOUR-USERNAME/TASK-REPO.git
cd TASK-REPO
```

**Make a branch named after yourself and your ID No.**
```bash
git checkout -b submission/your-name-2026AXPSXXXXH
```

**Do the task.** Put your work in the folder the task README specifies.

**Commit as you go — don't save it all for the end**
```bash
git add .
git commit -m "feat: implement wall-following logic"
```

**Push to your fork**
```bash
git push -u origin submission/your-name-2026AXPSXXXXH
```

**Open the Pull Request** — go to your fork on GitHub, hit `Compare & pull request`, and fill in the template. Title it:

```
[TASK NAME] Your Name - ID Number
```

</details>

> Commit **often**. Twenty small commits tell us how you think. One giant commit at 11:58 PM tells us nothing.

---

## What We're Actually Judging

<table>
<tr>
<td align="center" width="25%">

### Approach
Did you think about the problem, or pattern-match to a tutorial?

</td>
<td align="center" width="25%">

### Documentation
Can we understand your code from your Documentation?

</td>
<td align="center" width="25%">

### Craft
Clean, readable, sensibly structured

</td>
<td align="center" width="25%">

### Ambition and Vision
Did you push past the bare minimum?

</td>
</tr>
</table>

> **On AI tools:** Use them. Everyone does. But you will be asked in the interview to explain any line of your code. If you can't, that's the end of the conversation. Understand what you ship.

---

## Stuck?

<div align="center">

Getting stuck is the job. Staying stuck quietly is not.

<p>
<a href="https://chat.whatsapp.com/C2Yh6DJ0lxrBvXWOYl8uWG?s=cl&p=i&ilr=0&amv=0"><img src="https://img.shields.io/badge/WhatsApp_Group-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/></a>
<a href="https://www.instagram.com/arc_bphc/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
<a href="https://arc-bphc.netlify.app/"><img src="https://img.shields.io/badge/Website-1F6FEB?style=for-the-badge&logo=googlechrome&logoColor=white"/></a>
<a href="https://github.com/arc-bphc/2026-ARC-Induction/issues"><img src="https://img.shields.io/badge/Open_an_Issue-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

**Joint Secretary:** Yash Bhatt — `8057913891` · Kaveesh Chaudhary — `7028732814`

</div>

<details>
<summary><b>FAQ</b></summary>

<br>

**Do I need my own hardware?** No. Everything is simulated.

**My laptop is bad. Am I cooked?** No. The Docker environments are lightweight and there are lab machines available.

**Can I use libraries?** Yes, unless a task explicitly says otherwise. Read the task README.

**Can I work with a friend?** Discuss freely. Submit individually. Dont be oversmart and submit your friends code, I can guarantee we have people smarter than you.

**I've never written a line of code.** Start with the easy "Steel is Pure" (Mech) task, move on to the easy "Flesh is Week" (Elec) task and then move on to "The Machine Spirit" (CNI) easy task.

**I'm going to miss the deadline.** Submit whatever you have. A working 60% beats a missing 100%, every submission goes through a thorough review.

</details>

---

<div align="center">

### Build something you'd want to show off ;)

<sub>Automation & Robotics Club · BITS Pilani, Hyderabad Campus · 2026</sub>

<img src="https://img.shields.io/badge/Made_by-ARC-0D1117?style=flat-square"/>

</div>
