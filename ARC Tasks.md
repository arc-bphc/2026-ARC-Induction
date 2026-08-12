{Imperial Missive | 0626260.M27a}
# Welcome, Acolyte. 
Congratulations on passing the **Imperial Test**. Now begins your training to be a true member of the great order of **ARC**.
Fabricator General Maindola of the Forge World of BPHC has decreed that a minimum of 3 Trials must be completed by a Fresher Acolyte to become a part of our Sacred Order. Sophomore Acolyte's must complete a minimum of 4 Trials to be elgibile for elevation to the position of Tech Priest. 

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

#### Trial 1:
Welcome to SBoxx, A Hive City in the Cadian Sector. The Sacred Order of ARC is tasked with classifying settlements at every ration cycle. The settlements are classified as Live and Dead according to the Administratum Classification Codes of M25 as follows:

- Any Live Settlement with fewer than 2 neighbours dies.
- Any Live Settlement with 2 or 3 Live Neighbours lives on to the next ration
- Any Live Settlement with more than 3 Live Neighbours dies.
- Any Dead Settlement with exactly 3 Live Neighbours becomes a live cell.

Lord Inquisitor Bhatt and his Assistant, Lieutenant Priyadarshi have suddenly been recalled to an urgent meeting at the *Cadian Front*. They have left their work in 2 files, "src/solver.py". Complete their work to check the Settlements at a given coordinate and return the total number of Live Neighbours after checking the 8 surrounding Settlements. Look out for the edge of the Mapped Area.

Secondly, in the same file, use the Administratum Classification Codes of M25 and your previous work to generate and return a brand new Map, representing the state at the next Ration.

#### Trial 2:
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

[Electrical]   
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
You and Archmagos Gupta must converse with the elusive Tau. These Tau have not yet gained the ability to converse in High Gothic. They converse primarily using graph generators. Archmagos Gupta needs you to use the Sacred Op-Amp IC to create a Proportional-Integral-Derivative Controller using the [Imperial Circuit Tester](https://www.tinkercad.com/). The Tau have several samples from travellers long past, to let you parlay, you must translate them correctly. The Archmagos has provided you with an [STC InfoPad - PID](https://www.youtube.com/watch?v=tFVAaUcOm4I) regarding PID COntrollers and [STC InfoPad - OpAmp](https://www.youtube.com/watch?v=idJEMYhrIfs)  and this InfoPad on Op-Amps.

You must input the following functions on the Function Generator and show the outputs on Oscilloscope after Proportional, Integral, Derivative and PID stages individually. The functions are:

- Sine Test: Freq- 100Hz, Amplitude - 2.0 V, DC Offset - 0.0 V, Function: Sine
- Square Test: Freq- 50Hz, Amplitude - 2.5 V, DC Offset - 0.0 V, Function: Square
- Sawtooth Test: Freq- 100Hz, Amplitude - 2.0 V, DC Offset - 0.0 V, Function: Triangle
 

You must return the functions produced by your creation as a Word Document with Proper Labels. Be quick young Acolyte, for trade awaits.

***Praise be the Omnissiah!***   

