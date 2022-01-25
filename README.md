# HTTP Web Server

This is a simple HTTP web server that hosts very basic HTML pages. The objective of this work is to understand response header content-types, error codes and some methods of Node.js http module. Its a small module of a full stack website project. 

# Demo
![chrome_gYK1BAln0h](https://user-images.githubusercontent.com/87348490/150921487-f7ae6ef2-0393-4a29-80c9-f1516db11600.gif)



## Technologies Used

HTML, CSS, Node.js

## Lessons Learned
- Creating a basic HTTP web server.
- Learned about Response header content-type, error codes and some methods of Node.js http module.

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

