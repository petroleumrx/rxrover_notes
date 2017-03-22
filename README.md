# rxrover_notes


###### url:
- http://rxrover.petroleumrx.com/
- http://rxrover.petroleumrx.com/hunt
- http://rxrover.petroleumrx.com/hunttest
- http://rxrover.petroleumrx.com/rxdemo
- http://localhost/RxRover/app/ # local


###### where the git repo is in brian's computer:
- /c/Development/DriverApp/

###### and a testing copy for apache in brian's computer:
- C:\Apache24\htdocs\RxRover\


###### Where data is sent to by the app:
- /app/SyncData/5/


# implementation hints

###### client side database:
- pouchdb  (https://pouchdb.com/)

###### `/app` folder is for development
###### `/dist` folder is for production








# How to add changes:

- make changes in /c/Development/DriverApp/
- delete folder: /c/Development/DriverApp/dist
- run $ grunt prd
- use filezilla to connect to rxrover machine 
- locate jobber folder 
- delete all items in the jobber folder 
- move content in dist over 
- update api/config.php







-------------------


- run $grunt prd
- make sure no one is using rxrover for rxdemo
- in the server remove all items under rxdemo, EXCEPT importData and syncData
- copy the items of my local dist folder to the server
- Once copied over then change api/config.php in the server
