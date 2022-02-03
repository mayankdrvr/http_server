# HTTP Web Server

This is a simple HTTP web server that hosts very basic HTML pages. The objective of this work is to understand response header content-types, error codes and some methods of Node.js http module. Its a small module of a full stack website project. 

# Demo
![chrome_gYK1BAln0h](https://user-images.githubusercontent.com/87348490/150921487-f7ae6ef2-0393-4a29-80c9-f1516db11600.gif)

## Technologies Used

<a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a>
<a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> 
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a>
<a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> 

## Lessons Learned
- Creating a basic HTTP web server.
- Learned about response header content-type, error codes and some methods of Node.js http module.

## Authors

[@mayankdrvr](https://www.github.com/mayankdrvr)

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Run on Local System

- Clone the project
```bash
  git clone https://github.com/mayankdrvr/http_server.git
```
- Install Node.js from https://nodejs.org/en/download/ and install git bash from https://git-scm.com/downloads
- Go to the cloned folder in your local system and right click to select Git Bash Here.
- In git bash, run the command
```bash
  node server.js
```
- Go to http://localhost:1340/ to view the web server.
- If port:1340 is already occupied by some other process, it can be changed in server.js file in the listen() object of http module.

