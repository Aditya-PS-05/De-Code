### client side code
https://github.com/Aditya-PS-05/De-Code-client

### steps to run the repository
1.) Clone the two repositories in a folder 

### client side steps
3.) run npm install and npm run dev

### code-compiler steps
4.) Go to code-compiler 
5.) run npm install and npm run start

### Running docker file
6.) There is a dockerFile in the code-compiler folder
7.) Run docker build -t remote-adi .  
8.) Run docker run -d -p 8080:80 <name>:latest 
9.) Replace <name> to give the name of your choice
9.) It will run the docker file.

## End
10.) Now you can test the app

### Description
This app is build using Nextjs for frontend and backend and python for code-compilation. Currently this app only supports three languages (C++, Java and Python). Authentication is done using DAuth. So you can only use this app if you have DAuth access.

### Properties
1.) Authentication using DAuth
2.) Database setup for User and Problems both
3.) Problems solving dashboard -> where you can select a problem and solve it and check if it passes all the testcases or not

### Upcoming Properties
1.) User Dashaboard
2.) More Languages support
3.) Code submission
