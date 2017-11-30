# QuickNotes
Take notes without opening any editor or application and have them organized on your desktop in the form of sticky notes

## Background
While doing the MOOCs or reading any material online, manyatimes our mind ignites with a query, idea or some other work and commitments and for that purpose, we have to open either a text editor or a note taking application software in order to organize them and synchronize them with our devices. The best is to instantly write anything that comes into your mind without closing the window and just begin to type anything that you want and that will be replicated in the form of the note(s) on your desktop just like the sticky notes. Faciliating the hyperlink and email/evernote synchronization can be beneficial for us. Also, you can get the CPU beeps and the notification on your desktop too as the reminder.

## Installation
1. Clone the repository using the command `git clone https://github.com/dileepsankhla/QuickNotes.git`
2. cd `Key Logger` directory
3. run `make` to compile and make our basic keylogger
4. `cd .. && chmod +x shortcut.sh` to make the bash script executable
5. `./shortcut.sh` to run it and add the keylogger executable shortcut

You can view the keylogs for now in `/var/log/skeylogger.log`

### Note
We are using C++ for drawing and rendring the texts (notes) on the desktop and we have a couple of methods (low level and the high level) to render them beneath the desktop icons. We have to cover them into the rectangular boxes. We will focus on Qt for that.

## Instructions 

1. Upload the Arduino program present inside the same directory with the correct modifications if required.

2. Install LAMP or WAMP server and put all the files under the 'Server' directory in`var/www/html` or `C:\wwww` directory after the correct modifications if required.

3. Connect the system and the other mobile devices to the same wifi network.

4. Run the Python script first either by `sudo python2 script.py` or cmd -> run as administrator -> `python2 script.py` after changing to the script's directory.

5. Make sure your board is connected via USB. You can also open the Arduino IDE's serial monitor for debugging.

## Further Milestone
1. Hyperlink function
2. Synchronization using email or evernote api
3. Reminder with CPU Beeps
4. Packaging and uploading to PPA 

## Contribution 
This project consist of beginner to intermediate level issues. Feel free to comment on an issue and wait to be get assigned or you are welcome to open any new issue. For now, follow the installation steps.
