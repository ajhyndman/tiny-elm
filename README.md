# tiny-elm
A very minimal elm starter kit

## Tools

To start building stuff with this kit, you will need a few tools!

* git
* npm
* a command line (cmd on Windows or Terminal on MacOS come pre-installed!)

### git
[git](https://git-scm.com/) is a **version control application**.

This guide introduces both github (this site) and git, if you'd like an introduction!
http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/

You can download git from the official site: https://git-scm.com/downloads.

### npm
[npm](https://www.npmjs.com/) is a **package manager** for javascript projects.  You don't need to know too much about it now.

You can install npm (with node) from their official site: https://nodejs.org/en/download/.  (Feel free to install npm via tools like Homebrew, Chocolatey, or NVM if you are more comfortable with them, of course!)

## Starting Your Project

Now that you have a professional developement environment set up, lets get started!

Next you will need to open your command line and navigate to a folder where you would like to download this project.  This should be acheived by typing a command something like this:

```bash
cd C:/Users/YOUR_NAME/SOME/FOLDER
```

*Clone* the repository using this command:

```
git clone https://github.com/ajhyndman/tiny-elm.git
```

Move into the folder we just downloaded:

```bash
cd tiny-elm
```

Once you're there, install the project dependencies with npm!  This will take a minute or two.

```bash
npm install
```

Now, you're set up!  To build your application, use the helper script:

```bash
npm run build
```

To launch and view the application, use:

```bash
npm run server
```
