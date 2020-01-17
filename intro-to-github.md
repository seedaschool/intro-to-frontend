# Intro To GitHub and GitHub Pages

Questions
1. What is GitHub?
2. Who uses GitHub and why?
3. [What is GitHub Pages?](https://youtu.be/2MsN8gpT6jY)

### Create a GitHub Account

### Getting Started with GitHub Pages
1. Create a repository
  - Head over to GitHub and create a new repository named `username.github.io`, where username is your username (or organization name) on GitHub.
  - If the first part of the repository doesn’t exactly match your username, it won’t work, so make sure to get it right.

2. Clone the repository
  - Go to the folder where you want to store your project, and clone the new repository
  - Run this command in your terminal: `$ git clone https://github.com/username/username.github.io`

3. Add an Index file
  - Enter the project folder and add an `index.html` file:
  - `$ cd username.github.io`
  - `echo "I did it! Do a happy dance!" > index.html`

4. Push it
  - Add, commit, and push your changes:
  - `git add --all`
  - `git commit -m "Initial commit"`
  - `git push -u origin master`

5. Check out your website! Go to: https://username.github.io
