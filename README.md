# SYSdump
MSwindows batch script for live-forensic-acquisition

    +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
                                                                                                                                               
                                                                           dddddddd                                                              
       SSSSSSSSSSSSSSS YYYYYYY       YYYYYYY   SSSSSSSSSSSSSSS             d::::::d                                                              
     SS:::::::::::::::SY:::::Y       Y:::::Y SS:::::::::::::::S            d::::::d                                                              
    S:::::SSSSSS::::::SY:::::Y       Y:::::YS:::::SSSSSS::::::S            d::::::d                                                              
    S:::::S     SSSSSSSY::::::Y     Y::::::YS:::::S     SSSSSSS            d:::::d                                                               
    S:::::S            YYY:::::Y   Y:::::YYYS:::::S                ddddddddd:::::d uuuuuu    uuuuuu     mmmmmmm    mmmmmmm   ppppp   ppppppppp   
    S:::::S               Y:::::Y Y:::::Y   S:::::S              dd::::::::::::::d u::::u    u::::u   mm:::::::m  m:::::::mm p::::ppp:::::::::p  
     S::::SSSS             Y:::::Y:::::Y     S::::SSSS          d::::::::::::::::d u::::u    u::::u  m::::::::::mm::::::::::mp:::::::::::::::::p 
      SS::::::SSSSS         Y:::::::::Y       SS::::::SSSSS    d:::::::ddddd:::::d u::::u    u::::u  m::::::::::::::::::::::mpp::::::ppppp::::::p
        SSS::::::::SS        Y:::::::Y          SSS::::::::SS  d::::::d    d:::::d u::::u    u::::u  m:::::mmm::::::mmm:::::m p:::::p     p:::::p
           SSSSSS::::S        Y:::::Y              SSSSSS::::S d:::::d     d:::::d u::::u    u::::u  m::::m   m::::m   m::::m p:::::p     p:::::p
                S:::::S       Y:::::Y                   S:::::Sd:::::d     d:::::d u::::u    u::::u  m::::m   m::::m   m::::m p:::::p     p:::::p
                S:::::S       Y:::::Y                   S:::::Sd:::::d     d:::::d u:::::uuuu:::::u  m::::m   m::::m   m::::m p:::::p    p::::::p
    SSSSSSS     S:::::S       Y:::::Y       SSSSSSS     S:::::Sd::::::ddddd::::::ddu:::::::::::::::uum::::m   m::::m   m::::m p:::::ppppp:::::::p
    S::::::SSSSSS:::::S    YYYY:::::YYYY    S::::::SSSSSS:::::S d:::::::::::::::::d u:::::::::::::::um::::m   m::::m   m::::m p::::::::::::::::p 
    S:::::::::::::::SS     Y:::::::::::Y    S:::::::::::::::SS   d:::::::::ddd::::d  uu::::::::uu:::um::::m   m::::m   m::::m p::::::::::::::pp  
     SSSSSSSSSSSSSSS       YYYYYYYYYYYYY     SSSSSSSSSSSSSSS      ddddddddd   ddddd    uuuuuuuu  uuuummmmmm   mmmmmm   mmmmmm p::::::pppppppp    
                                                                                                                              p:::::p            
                                                                                                                              p:::::p            
                                                                                                                             p:::::::p           
                                                                                                                             p:::::::p           
                                                                                                                             p:::::::p           
                                                                                                                             ppppppppp           

    +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
    
      	tool author:  t0rt3rra    https://github.com/t0rt3rra
    
    	shout out to: carlospolop  for the legion tool that SYSdump is based on		https://github.com/carlospolop 
    		
    +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
    
    	about:
    		SYSdump is intended to aid forensic acquisition for live windows systems by parsing some of the more common settings 
    		and files on MSwindows systems using tools native to the windows command line.  as such, SYSdump will have a limited 
    		footprint on the target OS (if run from USB or external drive) and can dump the results file (SYSDUMPoutput.txt) onto 
    		an external drive or USB thus maintaining forensically-sound target acquisition.  Similarly, batch script is simple-
    		enough for the lay-person to understand and aids the forensic investigator's testimony in court to the tool's content
    		and its utility in parsing forensic artifacts.
    
    +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++



