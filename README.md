# Quick-Hotels
Its a hotel booking website where we can browse and book the most suitable hotel for us by using various filters,
Also all booking information is stored in cloud , to be accessed from anywhere

# STEPS FOR EXECUTION 

# Command to run backend
  * Download folders are zip and extract them
  * go to /backend directory in terminal and type "npm install" after that, "npm start"
  
          # IMPORTANT , IN CASE OF TEXT ENCODING ERROR AFTER RUNNING NPM START
	        GO TO :backend/node_modules/whatwg-url/lib/encoding.js
	        PASTE THIS BEFORE SECOND LINE : const {TextDecoder,TextEncoder} = require('util');
          Then try 'npm start' again
          
  * If you get message connected ! , backend is running, (dont close the terminal)

# Command to run frontend
  * This should be done after starting backend.
  * open another terminal in the extracted directory frontend and type "yarn" eafter that "yarn start"
  * The website will be opened automatically and it is ready to use !
  
  
# WEBSITE SAMPLE IMAGES,
  
HOMEPAGE (DETAILS CAN BE FILLED ONLY AFTER LOGGING IN/ SIGNING UP)


![home](https://user-images.githubusercontent.com/91386977/158021521-505f2407-aa98-4aa6-ba97-2aae80b67192.png)

	
SIGN UP PAGE

![sign_up](https://user-images.githubusercontent.com/91386977/158021544-793e12d3-b4fd-4426-8dab-e394e5734ff9.png)


ONCE LOGGED IN THIS PAGE APPEARS AND DETAILS CAN BE FILLED

![logged_in](https://user-images.githubusercontent.com/91386977/158021566-d1d359ff-b504-4955-b104-f38f27b3e6a3.png)


BASED ON THE DETAILS GIVEN HOTEL LIST IS DISPLAY WHICH CAN BE FILTED AND SORTED

![hotels](https://user-images.githubusercontent.com/91386977/158021619-8d9d3dd4-dcab-4462-a89f-a61f1d789b8d.png)


ALL BOOKINGS OF USER CAN BE ACCESSED FROM BOOKINGS SECTION

![bookings](https://user-images.githubusercontent.com/91386977/158021640-6c3a717c-8a50-442b-a249-32078f18eac7.png)
