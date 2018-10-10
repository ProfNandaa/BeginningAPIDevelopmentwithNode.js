# Lab 5: Using `nodemon`

In this lab, we’re going to introduce a Node module know as nodemon that we will be using to run our web server. This makes it possible for the server to automatically reload when we make changes to it, therefore saving us the tediousness of stopping the server and starting it over again manually, whenever we make changes to our server.

1. Go back to the terminal and stop the server (press Ctrl + C), the run the following command.
1. We will need to install this package globally (remember that you might need some administrative rights, so in unix systems, you need to run the command as sudo)

  ```bash
  npm install --global nodemon
  ```

3. Once installation is complete. We can now run with nodemon:

  ```bash
  nodemon server.js
  You should get something like:
  [nodemon] 1.12.1
  [nodemon] to restart at any time, enter `rs`
  [nodemon] watching: *.*
  [nodemon] starting `node server.js`
  Server running at: http://localhost:8000
  ```