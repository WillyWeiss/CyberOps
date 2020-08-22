

![](https://banner2.cleanpng.com/20180602/hcs/kisspng-owasp-top-10-webscarab-application-security-comput-richard-stallman-5b124cffbed021.8893118415279260157816.jpg)


# 
# XMPP and OWASP Mutillidae II installer on CyberOps and Kali Linux .


Welcome to the first installer for XMPP version 7.4.5 and OWASP Mutillidae II version 2.6.67 under CyberOps and Kali Linux.

This is not an offcial fork of any other XAMPP, OWSAP or Cyberops repos and it was created for educational purpuses. 

This repo is aimed to help University students on theyr Web Security Assignments. Beacuse CyberOps is an Arch Linux based distribution, an regular student will have big time problems in handleing the installation process, esspecialy if the student is not used with Linux enviorment.
Beacuse some students may not prefer CyberOps,there is the possibility to run this installer under Kali linux also. Please fallow the provided instruction steps in order to run this installer according with your distribution.

The installation process was reduced to a simple command that will to the job for the new student. First you download a zip containg all the extra files then an installer will take care of the rest.
## Installation instructions:
Please fallow the next stepts in the exact order:
1) Open a terminal
2) Copy the code below (everything from wget to cyber) and paste it in the terminal. Then press "ENTER":
`wget --load-cookies /tmp/cookies.txt "https://docs.google.com/uc?export=download&confirm=$(wget --quiet --save-cookies /tmp/cookies.txt --keep-session-cookies --no-check-certificate 'https://docs.google.com/uc?export=download&id=1sFEeyVAPWV0b-RBrrerZvI33JUuZYpjz' -O- | sed -rn 's/.*confirm=([0-9A-Za-z_]+).*/\1\n/p')&id=1sFEeyVAPWV0b-RBrrerZvI33JUuZYpjz" -O cyber.zip && rm -rf /tmp/cookies.txt && 7z x cyber.zip && cd cyber
`

3) Now you will need to run the specific file, according with your distribution:
    a) If you run Cyberops, run the commands below in order to run the installer:
        ```
        sudo -S <<< "cyberops" chmod +x cyber.sh
        ./cyber.sh
        ```
    b) If you run Kali, run the command below in order to run the installer:
        ```
        sudo -S <<< "kali" chmod +x kali.sh
        ./kali.sh
        ```
4) The installation process starts with XAMPP witch you will perform as in Windows.
IMPORTAN~~DO NOT LAUNCH THE XAMPP AFTER INSTALLATION.

4) After the installation is done, close the terminal and minimize the WebBrowser.

5) Right Click on the new icon (OWSAP-Mutillidae) and select PROPERTIES.

6) On the top click on the Permission. On the bottom there is a tickbox (Allow this file to run as a program). TICK THE BOX.

7) Click on Close Button. 

8) Open the OWSAP-Mutillidae (normal double click, like on any other icon)

9) No more excuses.....LEARN!

## 7 minutes of extra tutorial help presented in CyberOps:

Video Link is:


https://vimeo.com/418045369


Password is: 

4dv4nc3dW3bS3cur!7y

## Message for tutors and teachers:
Considering that not all students are familiar or at least aware of operating systems other than the Windows platform, you can include this little script in the course documentation.

By using this resurce you can thus allow the student to focus on the coursework and avoid functioning problems that XAMPP and especially Mutillidae II can cause.


