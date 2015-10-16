# chaconPlug
Repot that host Idleman script to play with Chacon outlet

This script allow to control Chacon DI-O outlet with an rf (433Mhz) transmitter plugged to a Raspberry Pi.
All the work has been done by Idleman (http://blog.idleman.fr/), many thanks to him for the HUGH work decrypting the protocol.
I have done nothing but to host it on Github. The goal of this repot is just to offer an easy way to get it.

To use it you need to have the magnificient ;) wiringPi library (http://wiringpi.com/) install on your system.

## WiringPi installation (In short):
    This help assume that you have the git-core package installed.
    
    Clone the wiringPi repot: git clone git://git.drogon.net/wiringPi
    Then go in the newly created folder : cd wiringPi
    Now you just need to build it! : ./build
    
    For a more complet explanation you can go to http://wiringpi.com/download-and-install/
    
## Compiling the script :
    This help assume that you have g++ and libc6-dev packages installed.

    Once you have install the wiringPi library, clone this repot : git clone https://github.com/Starlight42/chaconPlug.git
    Then go in the chaconPlug directory : cd chaconPlug
    Now you can compile the script : g++ rfSend.cpp -o rfSend -lwiringPi
    
## Using the script :
    You can find all the information on how the script work and how to use it here : http://blog.idleman.fr/raspberry-pi-12-allumer-des-prises-distance/
    Or even here : https://arno0x0x.wordpress.com/2015/04/02/rf433-outlet/
    
    
