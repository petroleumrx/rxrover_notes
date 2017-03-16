# rxrover_notes


###### Where data is sent to by the app:
- /app/SyncData/5/

###### url:
- http://rxrover.petroleumrx.com/


###### where the git repo is in brian's computer:
- /c/Development/DriverApp/


# How to add changes:

- make changes in /c/Development/DriverApp/
- delete folder: /c/Development/DriverApp/dist
- run $ grunt prd
- use filezilla to connect to rxrover machine 
- locate jobber folder 
- delete all items in the jobber folder 
- move content in dist over 
- update api/config.php
