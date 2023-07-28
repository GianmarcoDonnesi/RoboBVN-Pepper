**Introduction**
The code in this repository represents the result of research and development work carried out in the field during the implementation of the dissertation, which focused on the implementation of an innovative application for training patients with autism spectrum disorders (ASD). The code was implemented and leveraged to work on the humanoid robot Pepper from Softbank Robotics.

 **Description**

Specifically, two popular tests have been created and implemented:

- Auditory Discrimination Test
- Tower of London (TOL) test.
- 
**System Requirements**

To run the project properly, the following system requirements are needed:

- **Sistema operativo**: Windows 10/11 (preferred), Linux, macOS (poor compatibility from M1 chips).
- **Software**: Choregraphe (version 2.5 recommended)
- **Pacchetti**: PepperSDK

## **Project structure**
The project is organized as follows:

- **\SomministrazioneTest:** contains the code for Pepper implemented in Choregraphe for administering the two tests mentioned earlier.
- **\fotoTOL:** Folder containing photos shown on Pepper's tablet during the administration of the Tower of London (TOL) test

## **Code Usage**
To start the project, follow the steps below:

1. Start the sw Choregraphe
2. Check that your pc is connected on the same subnet as Pepper's
3. Click on the green "Connect to..." button to connect the Pepper robot
4. A new screen will appear that will allow you to click your version of pepper and be able to enter the robot's ip and its port. I recommend keeping the port set to default. While the ip must be spoken by pepper by pressing the button it has under the tablet. 
5. With that done, click on the "*Select*" button and the program will be connected to the robot. You will only realize it is connected when you notice in the upper left corner the phrase (Connected to "IPaddres"). Your robot will then appear in the **Robot view** (Robot view).
6. At this point you can load the *SomministrazioneTest* folder in the upper left corner by clicking the folder icon (Open Project) and it will be loaded into the program.
7. The specific file to open is **SomministrazioneTest.pml**

