**HFAero ICAO SELCAL Decoder V1.0.1**

_**What this program does**_

The HFAero SELCAL Decoder will decode SELCALs received via an HF receiver connected to your Windows PC via a sound card of sorts.  The decoded calls will be displayed inside the window and written to a file for archiving/recall later.  Successful decodes will return an associated airframe (Registration, Type and Operator Code) looked up from a file called selcal_lookup.txt.  The program will also, optionall, lookup a flight from **Flightaware** and if there is a current flight for the airframe (Registration) then the flight number and route will be displayed.  This SELCAL lookup file has been compiled from my personal reception logs and only confirmed when correlated via numerous sources.  There has been no skimming of databases, these are all my own collections from a year of listening!  Feel free to add to it, it is a TAB delimited text file.

The file that successful decodes is written to contains local time and UTC time.  I find UTC time invaluable when looking up possible flights from tracking sites which is why it is included.

The decoder requires that your receiver be aligned within **+/-8Hz** otherwise you will get no decodes or some miscodes.  Modern day SDRs such as **SDRPlay**, **AirspyHF+** and **KiwiSDR** should decode 'out of the box'.  Quality analogue receivers, especially commercial grade will also fair well if aligned correctly.  Older analogue receivers such as Icom R71, Kenwood R100 and the like may fare better with some fine tuning.  Of course this doesn't account for those ground stations with dubious transmitters that I've seen transmitting up to 20Hz away from the assigned frequency, nothing can be done about those!

_**Installation**_

Unzip the zip file contents to a folder of your choice and ensure you have write permissions to that folder or to the folder that will write the selcal_decodes.txt file.

_**Prerequisites**_

- Windows 11 (may work on other version but not tested)
- An audio input device such as Virtual Audio Cable, mixer, sound card etc.
- An HF receiver, analogue or SDR with the audio (speaker or line output) connected to your computer sound device.

_**Running the program**_

Double click the HFAero SELCAL Decoder.exe (or shortcut if created).  When the program opens select your audio input device that your receiver is connected to.

Select the folder containing selcal_lookup.txt (a green tick will tell you the program has found it).  By default this will be the folder you unzipped the contents to.

Select a folder for your selcal_decodes.txt file to be written to.  By default this will be the folder you unzipped the contents to.

There is an option to include a frequency so that one can see the frequency of each decode in the UI window and this frequency, if entered, will also be written to the selcal_decodes.txt file.

Tick or untick Flightaware lookup as desired.

You can also select a theme, System, Light or Dark to suit the users needs.

The window can be resized and the text will be, by default, automatically adjusted but there is also an option to manually adjust the font size if prefrred.  Also the top section containing the audio device selection, lookup file source, selcal_decodes.tx destination, text sizes and font colours can be minimised using the small arrow icon at the top of that section.  This helps to increase real estate on your PC.

And finally don't forget to press the green **Start** button!

_**Feedback**_

If you have any feedback or questions please email **selcal@mail2world.com**


