<div align="center">

<img src="Open Graph Image copy.png" width="120" alt="ARC Logo"/>

# ARC INDUCTIONS 2026

### Automation & Robotics Club · BITS Pilani, Hyderabad Campus

<p>
<img src="https://img.shields.io/badge/Status-OPEN-00C853?style=for-the-badge&labelColor=0D1117"/>
<img src="https://img.shields.io/badge/Deadline-18_08_2026-FF5252?style=for-the-badge&labelColor=0D1117"/>
<img src="https://img.shields.io/badge/Trials-6-2196F3?style=for-the-badge&labelColor=0D1117"/>

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

<a href="#tasks"><img src="https://img.shields.io/badge/_JUMP_TO_TASKS-1F6FEB?style=for-the-badge"/></a>
<a href="#how-to-submit"><img src="https://img.shields.io/badge/_HOW_TO_SUBMIT-238636?style=for-the-badge"/></a>
<a href="#stuck"><img src="https://img.shields.io/badge/_GET_HELP-8957E5?style=for-the-badge"/></a>

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
</div>

<details>
<summary><b> Click here to learn it the perfect way</b></summary>

<br>

| Resource | Why | Time |
|:---|:---|:---|
| **[Git and Github Basics](https://www.freecodecamp.org/news/git-and-github-for-beginners/)** | Absolute basics for git and github | ~10 min |
| **[Learn Git Branching](https://learngitbranching.js.org/)** | Interactive and visual. The fastest way to *understand* branching. Do the Introduction Sequence, no need to do everything. | ~10 min |
| **[GitHub: Hello World](https://docs.github.com/en/get-started/quickstart/hello-world)** | Walks you through your first repo and your first PR | ~10 min |
| **[Oh Sh*t, Git!?!](https://ohshitgit.com/)** | This is for when you inevitably get lost and dont know how to restore your work... | The time when you mess shit up |
| **[Conventional Commits](https://www.conventionalcommits.org/)** | Write commit messages that don't say "added stuff", Just read up on "Conventional Commits" | ~5 min |


<br>
</details>

---
Now, let us start with the tasks,  


# Welcome, Acolyte. 
 > {Imperial Missive | 0626260.M27a}     

Congratulations on passing the **Imperial Test**. Now begins your training to be a true member of the great order of **ARC**.
Fabricator General Maindola of the Forge World of BPHC has decreed that a minimum of 3 Trials must be completed by a Junior Acolyte to become a part of our Sacred Order. Sophomore Acolyte's must complete a minimum of 4 Trials to be elgibile for elevation to the position of Tech Priest. 

### Litany of the Machine
> The Flesh is Weak.   
> Steel is Pure.   
> Honor to the Machine Spirit   

Each part of the Litany is integral to the Sacred Order of ARC. Hence, Each Litany's Trial is split into 2 parts. An easier task, to demonstrate knowledge and the ability to learn. And a harder task, to show your proficiency in the Litanies, Hymns and Psalms of the Trial.

You may find the Trials attached below.    
**Glory to Holy Terra!**   
**Praise be the Omnissiah**

# Trial of the Machine Spirit
Henceforth lie the **Trial of the Machine Spirit**.   
Honor it, Pray to it or face it's ***Wrath***.

## Trial 1:
Welcome to SBoxx, A Hive City in the Cadian Sector. The Sacred Order of ARC is tasked with classifying settlements at every ration cycle. The settlements are classified as Live and Dead according to the Administratum Classification Codes of M25 as follows:

- Any Live Settlement with fewer than 2 neighbours dies.
- Any Live Settlement with 2 or 3 Live Neighbours lives on to the next ration
- Any Live Settlement with more than 3 Live Neighbours dies.
- Any Dead Settlement with exactly 3 Live Neighbours becomes a live cell.

Lord Inquisitor Bhatt and his Assistant, Lieutenant Priyadarshi have suddenly been recalled to an urgent meeting at the *Cadian Front*. They have left their work in 2 files, "src/solver.py". Complete their work to check the Settlements at a given coordinate and return the total number of Live Neighbours after checking the 8 surrounding Settlements. Look out for the edge of the Mapped Area.

Secondly, in the same file, use the Administratum Classification Codes of M25 and your previous work to generate and return a brand new Map, representing the state at the next Ration.

## Trial 2:
The Sacred Order of ARC had been asked to liason with the Phaeron Xun'Bakyr of the Maynarkh Dynasty of the Necrontyr. To meet with the Phaeron, you must first pass his test. You are given a dimensional teleportation cube, enabling you to perform the test without disturbing the environment. This revolutionary technology, called a DockerFile contains a Maze that you must solve. The maze is viewed through a Servitor present in the maze. You can communicate with the servitor through a comm-link known as ROS.

- You, along with Lord Inquisitor Bhatt and Assistant Ayyalasomayajula must use this file and the baseline script student_agent/solver.py to first discover the servitors interactions with the maze through the dimensional cube and the ROS comm-link.

- Next, in the baseline script, write a solver algorithm to guide the servitor through the maze. Changing the test itself, including the maze creator, the dimension generator or any other files will result in the Phaeron ordering an Exterminatus Strike on the nearest Hive City, killing trillions.

- Finally, to determine your competence, the Phaeron asks you to write a robust algorithm in the scan_callback function of solver.py that can consistently navigate the servitor into the green 2x2 exit zone.

To be gracious, the Phaeron has allowed you to modify the servitor, giving you a strict budget of 30 to make all stats. The stats are:

```
TOP_SPEED = 8
ACCELARATION = 7
TURN_SPEED = 5
SENSOR_RANGE = 10
```
Remember, the Servitor with fail if your stats exceed 30, you must balance these properly.

# Trial of the Pure Steel
tbd

# Trial of the Weak Flesh
tbd
##  How to Submit

<div align="center">

```
FORK → CLONE → BUILD → COMMIT → PUSH → PULL REQUEST
```


**Fork the task repository** — hit the `Fork` button at the top right of the task's page. Now you on a copy of the taks Repo. DO NOT FORK THIS REPO, FORK THE TASKS' REPO, YOU NEED TO ATTEMPT AND SUBMIT TASKS SEPERATELY.

**Clone your fork**
```bash
git clone https://github.com/YOUR-USERNAME/TASK-REPO.git
cd TASK-REPO
```

**Do the task.** We have provided proper templates for you to write your code, read every Task's Readme before attempting it.

**Commit as you go, don't save it all for the end**
```bash
git add .
git commit -m "feat: implement wall-following logic"
```

**Push to your fork**
```bash
git push
```

**Open the Pull Request** — go to your fork on GitHub, hit `Compare & pull request`, and fill in the template. Title it:

```
Your Name - ID Number
```
**wait for feedback and review**


> Commit **often**. Twenty small commits tell us how you think, which is a good advantage to have.

---
## Tasks 
<table width="100%">
<tr>
<td align="center" width="33%"><h3>MACHINE SPIRIT</h3></td>
<td align="center" width="33%"><h3>FLESH IS WEAK</h3></td>
<td align="center" width="33%"><h3>STEEL IS PURE</h3></td>
</tr>

<tr>
<td align="center">
<a href="https://github.com/arc-bphc/26-ARC-Inductions-GameOfLife"><img src="https://img.shields.io/badge/TASK_1-GAME_OF_LIFE-C0392B?style=for-the-badge&labelColor=8E2A1E&logo=python&logoColor=white" width="100%"/></a>
</td>
<td align="center">
<a href="https://github.com/arc-bphc/26-ARC-Inductions-MicromouseSim"><img src="https://img.shields.io/badge/TASK_1-ELEC_TASK-D4BE3E?style=for-the-badge&labelColor=A8942A&logo=arduino&logoColor=white" width="100%"/></a>
</td>
<td align="center">
<a href="LINK-3"><img src="https://img.shields.io/badge/TASK_1-MECH_TASK-17B5E0?style=for-the-badge&labelColor=1189AB&logo=autodesk&logoColor=white" width="100%"/></a>
</td>
</tr>

<tr>
<td align="center">
<a href="LINK-4"><img src="https://img.shields.io/badge/TASK_2-MICROMOUSE_MAZE-C0392B?style=for-the-badge&labelColor=8E2A1E&logo=ros&logoColor=white" width="100%"/></a>
</td>
<td align="center">
<a href="LINK-5"><img src="https://img.shields.io/badge/TASK_2-ELEC_TASK-D4BE3E?style=for-the-badge&labelColor=A8942A&logo=espressif&logoColor=white" width="100%"/></a>
</td>
<td align="center">
<a href="LINK-6"><img src="https://img.shields.io/badge/TASK_2-MECH_TASK-17B5E0?style=for-the-badge&labelColor=1189AB&logo=blender&logoColor=white" width="100%"/></a>
</td>
</tr>
</table>

## What We're Actually Judging

<table>
<tr>
<td align="center" width="33%">

### Approach
Did you think about the problem, or pattern-match to a tutorial?

</td>
<td align="center" width="33%">

### Craft
Code Quality and Understanding.

</td>
<td align="center" width="33%">

### Ambition and Vision
Did you push past the bare minimum.

</td>
</tr>
</table>

> **On AI tools:** You're allowed to use them. But you will be asked in the interview to explain any line of your code and your understanding of concepts and features of CAD software you used. If you can't, that's the end of the conversation. Understand what you submit, if you dont, then dont commit that part.

---

## Stuck?

<div align="center">

If you get stuck anywhere or have any issues, you can ask us:

<p>
<a href="https://chat.whatsapp.com/C2Yh6DJ0lxrBvXWOYl8uWG?s=cl&p=i&ilr=0&amv=0"><img src="https://img.shields.io/badge/WhatsApp_Group-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/></a>
<a href="https://www.instagram.com/arc_bphc/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
<a href="https://arc-bphc.netlify.app/"><img src="https://img.shields.io/badge/Website-1F6FEB?style=for-the-badge&logo=googlechrome&logoColor=white"/></a>
<a href="https://github.com/arc-bphc/2026-ARC-Induction/issues"><img src="https://img.shields.io/badge/Open_an_Issue-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

**Joint Secretaries:** Yash Bhatt — `8057913891` · Kaveesh Chaudhary — `7028732814`

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

### Make something you'd want to show off ;)

<sub>Automation & Robotics Club · BITS Pilani, Hyderabad Campus · 2026</sub>

<img src="https://img.shields.io/badge/Made_by-ARC-0D1117?style=flat-square"/>

</div>
