# Tailwind CSS - Empty Sandbox Project

A simple, empty project with everything needed for you to experiment with Tailwind CSS

## Pre-requesites

- You will need Node installed on your machine for this project to work. Download it [here](https://nodejs.org/en/download/).

- If you haven't done so already, install [live-server](https://github.com/tapio/live-server) globally on your machine by running the following command in your terminal:

```bash
npm install -g live-server
```

## Running the project

- Open two terminal windows simulatenously from the project directory. In VS Code, this can be achieved by clicking the icon highlighted below in the top right of your terminal window.

![Open additional terminal in VS Code](https://res.cloudinary.com/dptdx8zuv/image/upload/v1673698146/tailwind-css-sandbox/open-additional-terminal-in-vs-code_yw7yk0.png)

- Once open, you will see two terminal windows open side by side.

![Two terminals running simulatenously in VS Code](https://res.cloudinary.com/dptdx8zuv/image/upload/v1673698552/tailwind-css-sandbox/dual-terminal-in-vs-code_cwqnpy.jpg)

- In the first terminal window, run the following command:

```bash
npm run build
```

- Once this is running **AND WITHOUT CLOSING THE FIRST TERMINAL**, run the following in the second terminal:

```bash
npx live-server public
```

- Once both commands are running simultenously in their respective terminal windows, your browser will open and you should see a blue 'Hello World!' h1 element at the top of the screen.

## Happy editing!
