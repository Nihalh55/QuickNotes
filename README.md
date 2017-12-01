# `01 Dec 2017 03:16 PM IST` : The codebase is under maintenance as some intial changes have to be made in the codebase and the updated installation and the basic usage guide for the contributors is to be changed accordingly. Make sure to re-visit the issues and the code in 5 hours.

## For KWoC students, reach to me at the communication channel given [here] 
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

## Further Milestone
1. Hyperlink function
2. Synchronization using email or evernote api
3. Reminder with CPU Beeps
4. Packaging and uploading to PPA 

## Contribution 
This project consist of beginner to intermediate level issues. Feel free to comment on an issue and wait to be get assigned or you are welcome to open any new issue. For now, follow the installation steps.

[here]:https://groups.google.com/forum/#!forum/quicknotes
