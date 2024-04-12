SME-Assignment
Documentation
Task 1

Following the provided instructions to integrate the SFML Headers and library. The process involved:
Copying the header and lib folders from the SFML zip file.
Pasting them into the sfml folder.
After completing the integration, I attempted to run the .sln file in Visual Studio. 
The compilation process took approximately 15 minutes.

Task 2

During the project setup, I encountered errors in the PlayerController.h file. The errors were:
Syntax error: missing ';' before '*'
Unexpected token(s) preceding ';'
Despite conducting a thorough examination, I was unable to identify the exact cause of these errors. Initially, I suspected the issues might be within PlayerController.h. However, upon inspection, the file appeared to be correct.

The "unexpected token(s) preceding ';'" error indicated that the compiler could not recognize PlayerView and PlayerModel as valid types during pointer declaration. Both these classes are properly defined in the source/Player directory.
Additionally, I observed that my .exe file was missing while adding bin files to x64/debug. This could have potentially affected the local project setup.
The troubleshooting and resolution of these issues consumed approximately 3 hours of my time.

Task 3

To enable the firing functionality for the player ship, I performed the following actions:
Uncommented the firing implementation in the processPlayerInput() method within PlayerController.cpp.
Implemented the fireFrostBeam() method in SubzeroController.cpp to allow Subzero to fire FrostBeam.
Implemented the fireTorpedoes() function in ThunderSnakeController.cpp to enable firing heavy damage bullets.
Implemented the fireLockedMissiles() method in zapperController.cpp for locked-on missiles targeting the player.
The implementation of these firing functionalities took approximately 50 minutes.
