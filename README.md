# Json-Server_For_Angular_app

Configuring the Server
At any convenient location on your computer, create a new folder named json-server, and move to this folder.
Download the db.json file provided above to this folder.
Move to this folder in your terminal window, and type the following at the command prompt to start the server:

json-server --watch db.json -d 2000

http://localhost:3000/dishes
http://localhost:3000/promotions
http://localhost:3000/leaders
http://localhost:3000/feedback

Type these addresses into the browser address and see the JSON data being served up by the server. This data is obtained from the db.json file
Serving up the Images
The json-server also provides a static web server. Any resources that you put in a folder named public in the json-server folder above, will be served by the server at the following address:

http://localhost:3000/

http://localhost:3000/images/<image name>.png
