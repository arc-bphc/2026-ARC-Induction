<div align="center">

<img src="Open Graph Image copy.png" width="120" alt="ARC Logo"/>

# ARC INDUCTIONS 2026

### Automation & Robotics Club · BITS Pilani, Hyderabad Campus

<p>
<img src="https://img.shields.io/badge/Status-OPEN-00C853?style=for-the-badge&labelColor=0D1117"/>
<img src="https://img.shields.io/badge/Deadline-01_09_2026-FF5252?style=for-the-badge&labelColor=0D1117"/>
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
Henceforth lies the **Trial of the Pureness of Steel**. Your will must be strong as Steel, Unwieldy yet Versatile. Temper yourself, shall you find yourself embroiled in it's **Pain**

#### Trial 1:
Lord Kaveesh, Baron of Ultramar has tasked The Sacred Order of ARC with outfitting a part of his personal army. The Ultramarian forgeworld has misplaced the blueprint of his preferred design, as such you must refer to the STC InfoPad below and follow it exactly as you are told to. Remember, STC creations are perfect for the Golden Age. You must copy it exactly and then, and only then may you add some ... modifications to your design.

[STC InfoPad](https://www.youtube.com/watch?v=ZmckF8zYbp0)

And remember, if you fail, you must answer to Fabricator General Maindola yourself and perhaps we shall gain a new servitor.

#### Trial 2:
Lord Kaveesh, Baron of Ultramar requires you to develop a mechanical machine to launch a 10KG Melta Bomb on the battlefield of Cadia. You must design such a machine to take immense load of handling such battlefield carnage without the use of electronics, owing to high warp disruptions at the Front.    
In his infinite wisdom, Lord Kaveesh has given you the freedom to choose your own launching mechanism.   
And of course, the stronger, smarter and more innovative your .... machine is, the happier Lord Kaveesh will be.

Contained below is a list of objectives your machine must accomplish.
- 10 KG Melta Payload, assume it to be a block or cylinder
- Base chassis as strong as a Sister's Faith
- Moving Structural members/ mechanical stop or locking mechanism
- Reinforced pivot or hinge
- Proper rotational/translational joints
- Energy storage and release mechanism. 

Fabricator General Maindola requires rigorous testing of this machine before it is given to Baron Kaveesh. You must perform FEA as per Administratum Model CAD Code of M22. Find below, an attached STC InfoPad on FEA.

[AMCADC-FEA](https://www.youtube.com/watch?v=Srr1KYU_E-k)

You must: 
- Fix the Base Securely
- Apply an equyivalent dynamic load representing the peak launch forces generated by the Melta Bomb.
- Consider contact and collision loads of your mechanism in case of mechanical stops.
- Perform a Structural Stress Analysis(Administratum Model CAD Code)

You must Focus on:
- Pivot Pins and Hinge Stress
- Bending of the Main component
- Stress Concentrations
- Overall Safety Factor

Note: If your machine explodes before the Melta is Launched, You've just wasted Imperium resources and your Servitorization is Inevitable.

# Trial of the Weak Flesh
Henceforth lie the Trials of the Weakness of Flesh. Be warned, these are not for the faint of heart, or those sentimental of the blasphemy of ***skin***. You must remake yourself in the image of the Omnissiah.
Find the tasks below:

#### Task 1: 
Welcome to the ForgeWorld of Archmagos Gupta, a primary supplier of the Chapter Master Deshmukh's Blood Angels. He has tasked you with using the [Imperial Circuit Tester](https://www.tinkercad.com/).

But first, Young Acolyte, you must go through mandatory Psycho-Training. Find the STC links below. You may opt for either option, but beware for one might give you more pain than the other.

1) [Quick but Painful](https://www.youtube.com/watch?v=BLrHTHUjPuw)
2) [Slow and Steady](https://www.youtube.com/playlist?list=PLGs0VKk2DiYw-L-RibttcvK-WBZm8WLEP)

You must utilize 2 Arduino Boards for this circuit in a Master-Slave configuration. one Arduino has all the sensors, while the other has a lcd screen and a ir sensor with a remote. You must integrate a photoresistor, a gas sensor, a servo motor and a temperature sensor into the sensing arduino. The Archmagos plans to use these to monitor his more volatile projects and mines.

***The Sacred States of Operation***

Archmagos Gupta dictates that this apparatus must operate as a flawless State Machine to ensure Chaptermaster Deshmukh's armaments do not inadvertently detonate. Design your logic utilizing the following machine states:

*   **State 0: DORMANCY**
    *   Upon receiving power, the system enters a state of restful readiness. 
    *   The sensors are powered but inactive, awaiting the proper activation rites. 
    *   The LCD screen must display **"AWAITING RITUAL"**.
    *   The system remains in this state until a specific awakening command is received via the IR remote.

*   **State 1: VIGILANCE**
    *   Initiated by the IR remote, the Master Arduino commands the Slave Arduino to begin active scanning.
    *   The system continually polls the photoresistor and the gas sensor.
    *   The IR remote can be used to toggle the LCD display between showing ambient light levels and atmospheric purity percentages. 

*   **State 2: MIASMA**
    *   If the gas sensor detects >130 units of volatile compounds or toxic fumes, the system enters this state.
    *   The LCD screen must immediately override standard telemetry to display **"TOXIC PURGE"**.
    *   This state remains active until the gas levels drop below the acceptable safety threshold, at which point the machine returns to State 1.

*   **State 3: SHADOW-FALL**
    *   If the photoresistor detects a sudden, absolute drop in ambient light, assuming a mine collapse or deliberate sabotage by the enemies of Man, this state is triggered.
    *   The LCD must display **"NOCTIS PROTOCOL"**.
    *   The system will ignore standard IR commands until lighting is restored, logging the blackout event.

*   **State 4: EXTREMIS**
    *   If the temperature sensor registers above **45°C**, the system instantly transitions to this state.
    *   This state takes ultimate and absolute precedence over States 0, 1, 2, and 3.
    *   The LCD screen must immediately display **"COOKED"**.
    *   The servo motor must actuate to 180 degrees to engage the emergency physical venting mechanisms.
    *   This state requires a button press on the IR Remote to be resent. 

    In case of a combination of any of these events other than extremis, you must indicate the state as **MULTIPLE PROBLEMS DETECTED**, the state must change to the appropriate one if the sensor readings change. Also add a buzzer to blare in this case.


#### Task 2:
You and Archmagos Gupta must converse with the elusive Tau. These Tau have not yet gained the ability to converse in High Gothic. They converse primarily using graph generators. Archmagos Gupta needs you to use the Sacred Op-Amp IC to create a Proportional-Integral-Derivative Controller using the [Imperial Circuit Tester](https://www.tinkercad.com/). The Tau have several samples from travellers long past, to let you parlay, you must translate them correctly. The Archmagos has provided you with an [STC InfoPad - PID](https://www.youtube.com/watch?v=tFVAaUcOm4I) regarding PID Controllers and [STC InfoPad - OpAmp](https://www.youtube.com/watch?v=idJEMYhrIfs)  and this InfoPad on Op-Amps.

You must input the following functions on the Function Generator and show the outputs on Oscilloscope after Proportional, Integral, Derivative and PID stages individually. The functions are:

- Sine Test: Freq- 100Hz, Amplitude - 2.0 V, DC Offset - 0.0 V, Function: Sine
- Square Test: Freq- 50Hz, Amplitude - 2.5 V, DC Offset - 0.0 V, Function: Square
- Sawtooth Test: Freq- 100Hz, Amplitude - 2.0 V, DC Offset - 0.0 V, Function: Triangle
 

You must return the functions produced by your creation as a Word Document with Proper Labels. Be quick young Acolyte, for trade awaits.

***Praise be the Omnissiah!***     
##  How to Submit

<div align="center">

```
FORK → CLONE → BUILD → COMMIT → PUSH → PULL REQUEST
```


**Fork the task repository** — hit the `Fork` button at the top right of the task's page. Now you on a copy of the tasks Repo. DO NOT FORK THIS REPO, FORK THE TASKS' REPO, YOU NEED TO ATTEMPT AND SUBMIT TASKS SEPERATELY. ALSO, YOU HAVE TO FORK THE REPO THEN START YOUR WORK ON YOUR OWN FORK..

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
<a href="https://github.com/arc-bphc/ARC-Inductions-2026-Electrical-State-Machine"><img src="https://img.shields.io/badge/TASK_1-ARDUINO_MONITORING_SYSTEM-D4BE3E?style=for-the-badge&labelColor=A8942A&logo=arduino&logoColor=white" width="100%"/></a>
</td>
<td align="center">
<a href="https://github.com/arc-bphc/2026-ARC-Inductions---Robotic-Gripper"><img src="https://img.shields.io/badge/TASK_1-ROBOTIC_GRIPPER-17B5E0?style=for-the-badge&labelColor=1189AB&logo=autodesk&logoColor=white" width="100%"/></a>
</td>
</tr>

<tr>
<td align="center">
<a href="https://github.com/arc-bphc/26-ARC-Inductions-MicromouseSim"><img src="https://img.shields.io/badge/TASK_2-MICROMOUSE_MAZE-C0392B?style=for-the-badge&labelColor=8E2A1E&logo=ros&logoColor=white" width="100%"/></a>
</td>
<td align="center">
<a href="https://github.com/arc-bphc/ARC-Inductions-2026-OpAmp-PID/tree/main"><img src="https://img.shields.io/badge/TASK_2-PID_USING_OpAmp-D4BE3E?style=for-the-badge&labelColor=A8942A&logo=espressif&logoColor=white" width="100%"/></a>
</td>
<td align="center">
<a href="https://github.com/arc-bphc/2026-ARC-Inductions---High-Energy-Payload-Launcher"><img src="https://img.shields.io/badge/TASK_2-Payload_Launcher-17B5E0?style=for-the-badge&labelColor=1189AB&logo=blender&logoColor=white" width="100%"/></a>
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

**I've never written a line of code.** Start with the easy "Steel is Pure" (Mech) task, move on to the easy "Flesh is Weak" (Elec) task and then move on to "The Machine Spirit" (CNI) easy task.

**I'm going to miss the deadline.** Submit whatever you have. A working 60% beats a missing 100%, every submission goes through a thorough review.

</details>

---

<div align="center">

### Make something you'd want to show off ;)

<sub>Automation & Robotics Club · BITS Pilani, Hyderabad Campus · 2026</sub>

<img src="https://img.shields.io/badge/Made_by-ARC-0D1117?style=flat-square"/>

</div>
