Welcome to BrainBay !
---------------------

BrainBay is an open source bio- and neurofeedback application. It also offers
some features for the creation of alternative Human-Computer-Interfaces (HCIs) 
such as facetracking via webcam, EMG signal pattern recognition or mouse-/keyboard control.

All source code is licensed under GPL, for copyright information 
please have a look at ReadMe_License.txt

Version Info
------------
 
* The current release version is 2.1  (2017-09-23)

* Recent changes:
  * Support for OpenBCI Ganglion and the new OpenBCIHub
  * Support for Neurosky devices
  * Cursorkey integration for Oscilloscope and Threshold Windows
  * Oscilloscope features snapshots for training reporting
  * SessionManager and Sessiontime elements for menu-based selection of design

Link to Release and other Infos
-------------------------------

* Download latest release: https://github.com/ChrisVeigl/BrainBay/releases

* The release contains an installer for windows. In addition, the 'bin' folder of the github source repo contains an up-to-date executable file (BrainBay.exe)
  The 'bin' folder also contains the user- and developer manuals (.pdf).

* If you want to use BrainBay with the OpenBCI Ganglion, install the OpenBCIHub fist - have a look at:
  - http://docs.openbci.com/OpenBCI%20Software/01-OpenBCI_GUI#the-openbci-gui-installing-the-openbci-gui-as-a-standalone-application-install-openbci_gui-on-windows
  
* Useful info if you want to run BrainBay under Linux:
  - http://www.autodidacts.io/use-openbci-with-brainbay-on-ubuntu-linux-and-wine/

* Other related infos:
  - https://sites.google.com/site/biofeedbackpages/brainbay-openbci
  - http://openbci.com/forum/index.php?p=/discussion/90/brainbay-install-neurofeedback-tutorial
  - http://eeghacker.blogspot.co.at/2013/11/brainbay-eeg-visualization-software.html

* If you want to modify or extend the software, the Visual Studio 2010
  project files and all source modules are located in the 'src' folder.


Credits
-------

* Jim Peters for his marvellous filter-works (http://uazu.net/fiview/)
* Jeremy Wilkerson for programming some BrainBay Objects and MinGW/WINE support
* Jeff Molofee (NeHe) for this great OpenGl-tutorial (http://nehe.gamedev.net)
* Don Cross for a well working fft-routine (http://www.intersrv.com/~dcross/fft.html)
* AllenD for showing how to do a thread-oriented Com-Handler in Win32
* Craig Peacock for the the PortTalk I/O-driver, see http://www.beyondlogic.org 
* Marcin Kocikowski for the Neurobit Optima-4 Device and support
* Raymond Nguyen for the vector port additions
* Franz Strobl for the OCZ NIA support
* Stephan Gerhard for the QDS parser
* William Croft (OpenBCI) for various 2014 fixes, enhancements and blog posts


Further Information
-------------------

* Find documentation on the project hompage http://brainbay.lo-res.org
and in the user and developer manuals.
I also recommend having a look at the OpenEEG site http://openeeg.sf.net
and the OpenBCI project: http://www.openbci.org

* If you want to share your BrainBay design files for neurofeedback or biofeedback
protocols, I would be happy to include them in the release.


Enjoy :-)

Chris Veigl
contact: chris@shifz.org

