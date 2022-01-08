# SYSdump
## MSwindows batch script for live-forensic-acquisition


+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

      /$$$$$$  /$$     /$$ /$$$$$$        /$$                                  
     /$$__  $$|  $$   /$$//$$__  $$      | $$                                  
    | $$  \__/ \  $$ /$$/| $$  \__/  /$$$$$$$ /$$   /$$ /$$$$$$/$$$$   /$$$$$$ 
    |  $$$$$$   \  $$$$/ |  $$$$$$  /$$__  $$| $$  | $$| $$_  $$_  $$ /$$__  $$
    \____  $$   \  $$/   \____  $$| $$  | $$| $$  | $$| $$ \ $$ \ $$| $$  \ $$
    /$$  \ $$    | $$    /$$  \ $$| $$  | $$| $$  | $$| $$ | $$ | $$| $$  | $$
    |  $$$$$$/    | $$   |  $$$$$$/|  $$$$$$$|  $$$$$$/| $$ | $$ | $$| $$$$$$$/
    \______/     |__/    \______/  \_______/ \______/ |__/ |__/ |__/| $$____/ 
                                                                    | $$      
                                                                    | $$      
                                                                    |__/      
           
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
     
   shout out to: carlospolop  for the WinPE tool that SYSdump is based on		https://github.com/carlospolop/winPE
    		
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
    
   about:
   
   SYSdump is intended to aid forensic acquisition for live windows systems by parsing some of the more common settings and files on MSwindows systems using tools native to the windows command line.  the tool itself is based on an enumeration script, WinPE, which leverages Windows Internals commands.  as such, SYSdump will have a limited footprint on the target OS (if run from USB or external drive) and can dump the results file (SYSDUMPoutput.txt) onto an external drive or USB thus maintaining forensically-sound target acquisition.  Similarly, batch script is simple-enough for the lay-person to understand and aids the forensic investigator's testimony in court to the tool's content and its utility in parsing forensic artifacts.
    
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++



