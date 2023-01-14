# Tailwind CSS - Empty Sandbox Project

A simple, empty project with everything needed for you to experiment with Tailwind CSS

## Pre-requesites

- You will need Node installed on your machine for this project to work. Download it [here](https://nodejs.org/en/download/) if you haven't installed it already.

- We are using VS Code as our IDE, which can be downloaded [here](https://code.visualstudio.com/download) if you need it.

- Fianlly, we are also using Github Desktop for ease of use (this is aimed at beginners). Download it [here](https://desktop.github.com/) if you need this.

## Cloning in Github Desktop

- In Github Desktop, select `File > Clone Respository` from the menu.

- In the dialogue box that appears, clone the project somewhere on your machine outside of OneDrive, or any other folder that will automatically sync to the cloud. It's best to find your _Username_ folder, and create a subdirectory there called 'development' that you can house everything in.

![Clone repository in Github Desktop](https://res.cloudinary.com/dptdx8zuv/image/upload/v1673700484/tailwind-css-sandbox/clone-repo-in-github-desktop_ggkrss.jpg)

## Installing Packages in the Project Folder

- Open the newly cloned project file in VS Code. You can do this directly from Github Desktop for convenience:

![Open repository in VS Code from Github Desktop](https://res.cloudinary.com/dptdx8zuv/image/upload/v1673701334/tailwind-css-sandbox/open-vs-code-from-github-desktop_upw4ju.jpg)

- Once VS Code is open, run the command below in your VS Code terminal to install the npm packages required:

```bash
npm install
```

- If you haven't already, install [live-server](https://github.com/tapio/live-server) globally on your machine by running the following command in your terminal:

```bash
npm install -g live-server
```

## Running the project

- Open two terminal windows simulatenously from the project directory. In VS Code, this can be achieved by opening the project in the application and clicking the icon highlighted below in the top right of your terminal window.

![Open additional terminal in VS Code](https://res.cloudinary.com/dptdx8zuv/image/upload/v1673698146/tailwind-css-sandbox/open-additional-terminal-in-vs-code_yw7yk0.png)

- Once open, you will see two terminal windows open side by side.

![Two terminals running simulatenously in VS Code](https://res.cloudinary.com/dptdx8zuv/image/upload/v1673698552/tailwind-css-sandbox/dual-terminal-in-vs-code_cwqnpy.jpg)

- In the left terminal window, run the following command:

```bash
npm run build
```

- Once this is running **AND WITHOUT CLOSING THE LEFT TERMINAL**, run the following in the right terminal:

```bash
npx live-server public
```

- Once both commands are running simultenously in their respective terminal windows, your browser will open and you should see a blue 'Hello World!' h1 element at the top of the screen.

## Quitting the application

To quit the application, click into the left terminal window and hit `CTRL + c`. If you are asked `Terminate batch job? (Y/N)` just hit `y` on your keyboard. Repeat this process in the right-hand terminal.

## Happy editing!
