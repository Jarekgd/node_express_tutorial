# From youtube tutorial: Node.js and Express.js - Full Course 
[Link to the tutorial](https://www.youtube.com/watch?v=Oe421EPjeBE&t=3990s "Node.js and Express.js - Full Course ")

1. node_modudels don't have to be pushed to github .<br>
   To avoid pushing add '.gitignore' file with text: '/node_modules' <br>
   Eventually select ignore Node when creating a repository to ignore more.
2. commands to push new project:
   1. git init
   2. git add README.md
   3. git commit -m "First commit"
   4. git branch -M main
   5. git remote add origin git@github.com:Jarekgd/node_express_tutorial.git
   6. git push -u origin main
3. Install dev dependencies (requred only during development process - like tsting, code formatting, not usefull for a final product funcionality) eg. nodemon: 'npm i nodemon -D' or 'npm i nodemon --save-dev'
4. In package.json:<br>
   "scripts": {
    "start": "node app.js",
    "dev": "nodemon app.js"
  },<br>
   Allows to start from: 'npmstart' or 'npm run dev'
   nodemon automatically refresh command line after saving.
5. To uninstall package eg.: 'npm uninstall bootsrtap'
