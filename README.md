# linux-desktop-insanity
Solutions for annoying Linux desktop issues

I've been using Linux for over 2 decades as my desktop OS and for quite some time now my distribution of choice has been Ubuntu. Despite all these years I still find the upgrade process to be extremely frustrating and for every step forward there seems to be several steps backwards. Rather than continually being frustrated every day by these little issues, I've decided to do what I can to resolve these usability disasters. That's the open source way, right?

Current issue list (somewhat of a rant, based on level of annoyance):
* The file open dialog in gedit no longer opens to the directory of the current file. This worked great in Ubuntu 20.04, where you could switch to the tab of an open file and the file dialog would open to the same directory of the selected file. Now it is absolute garbage and I often use the command line to open files in gedit, versus navigating from some seemingly random useless file location to where I want to be for the 100th time or attempting to make use of the very busted "recent files" sewage factory catastrophe.
* GTK file open/save dialog search is busted. Typing characters into the recent file search causes the list to dissappear. Yes, the GTK file dialog has never achieved greatness.
* Moving dialogs will often attempt to move the parent window as well. Whoever thought this was a good idea, deserves what is coming to them in the afterlife for how much pain and suffering it is likely causing and the years of lost productivity. How many potential Linux users have abandoned the idea of trying to use it because of this dumpster fire? Seriously though, WTH? Like how is this helpful, like EVER?! Typical scenario:
  * Attempting to extract zip archive in file roller
  * File browser dialog pops up to select the directory to extract to
  * Oh, let's create a directory for the zip archive
  * What was the archive name again?
  * Ohh, it's obscured by the file dialog, I'll just move it out of the way so I can see the files in the main window..
  * Main window moves with file dialog... WT #U(@!
  * OK, looks like I can resize it really small so I can see the file names now.
* Dragging a window to the left or right side of the desktop usually maximizes it to half the screen. Ubuntu 20.10 added the annoyance of the window often switching screens in the process. It worked great before, why break it?
* gedit syntax highlight often locks up unexpectedly and sometimes gives up when typing in documents. Worked great in Ubuntu 20.04.
* Firefox will suddenly out of nowhere force you to restart it, saying "We've performed some upgrades"..  Yeah, probably just need to turn off some obscure setting, but who thought this was a good idea? What other application in the history of computing forces a restart, besides MS Windows?
* Why are Firefox menus so navigationally impaired? Like, I just want to open the dang tab I just accidently closed, but it seems I have to navigate through 3 levels of menus to get there.
