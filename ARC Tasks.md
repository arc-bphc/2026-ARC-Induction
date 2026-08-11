{Imperial Missive | 0626260.M27a}
# Welcome, Acolyte. 
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

[CNI]  
Henceforth lie the **Trial of the Machine Spirit**.   
Honor it, Pray to it or face it's ***Wrath***.

Trial 1:
Welcome to SBoxx, A Hive City in the Cadian Sector. The Sacred Order of ARC is tasked with classifying settlements at every ration cycle. The settlements are classified as Live and Dead according to the Administratum Classification Codes of M25 as follows:

- Any Live Settlement with fewer than 2 neighbours dies.
- Any Live Settlement with 2 or 3 Live Neighbours lives on to the next ration
- Any Live Settlement with more than 3 Live Neighbours dies.
- Any Dead Settlement with exactly 3 Live Neighbours becomes a live cell.

Lord Inquisitor Bhatt and his Assistant, Lieutenant Priyadarshi have suddenly been recalled to an urgent meeting at the *Cadian Front*. They have left their work in 2 files, "src/solver.py". Complete their work to check the Settlements at a given coordinate and return the total number of Live Neighbours after checking the 8 surrounding Settlements. Look out for the edge of the Mapped Area.

Secondly, in the same file, use the Administratum Classification Codes of M25 and your previous work to generate and return a brand new Map, representing the state at the next Ration.

Trial 2:
The Sacred Order of ARC had been asked to liason with the Phaeron Xun'Bakyr of the Maynarkh Dynasty of the Necrontyr. To meet with the Phaeron, you must first pass his test. You are given a dimensional teleportation cube, enabling you to perform the test without disturbing the environment. This revolutionary technology, called a DockerFile contains a Maze that you must solve. The maze is viewed through a Servitor present in the maze. You can communicate with the servitor through a comm-link known as ROS.

- You, along with Lord Inquisitor Bhatt and Assistant Ayyalasomayajula must use this file and the baseline script student_agent/solver.py to first discover the servitors interactions with the maze through the dimensional cube and the ROS comm-link.

- Next, in the baseline script, write a solver algorithm to guide the servitor through the maze. Changing the test itself, including the maze creator, the dimension generator or any other files will result in the Phaeron ordering an Exterminatus Strike on the nearest Hive City, killing trillions.

- Finally, to determine your competence, the Phaeron asks you to write a robust algorithm in the scan_callback function of solver.py that can consistently navigate the servitor into the green 2x2 exit zone.

To be gracious, the Phaeron has allowed you to modify the servitor, giving you a strict budget of 30 to make all stats. The stats are:

```
TOP_SPEED = 
ACCELARATION = 
TURN_SPEED = 
SENSOR_RANGE = 
```
Remember, the Servitor with fail if your stats exceed 30, you must balance these properly.

[Mechanical]

