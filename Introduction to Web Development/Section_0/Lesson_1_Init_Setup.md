# Initial Setup

## Cloning the Repository

To get started, we need to clone the ✨special✨ repository that contains all of the project files. To do this, we need to run the following command in our terminal:

```bash
git clone https://github.com/SAIS-Hack-Club/website-starter.git
```

*P.S. I suggest making a folder called `Projects` or something similar, and then cloning the repository into that folder. This will make it easier to find the project files later on. To do this, we can run the following command:*

```bash
cd Documents
mkdir Projects
cd Projects
git clone ...
```

This will create a new folder called `website-starter` in our current directory. We can change into this directory by running the following command:

```bash
cd website-starter
```

## What's in the Repository?

Now that we've cloned the repository, let's take a look at what's inside. We can do this by running the following command:

```bash
tree
```

This will print out a tree-like structure of all of the files and folders in the repository. Here's what it looks like:

```bash
.
├── assets
│   └── images
│       ├── [ ... ]
│   └── styles
│       ├── [ ... ]
├── .gitignore
├── LICENSE
└── index.html
```

*P.S. If you don't have `tree` installed, you can see the contents of the repository by running the following command:*

```bash
ls -R
```

*You will get a slightly different output, but it will still give you an idea of what's in the repository.*

Let's take a look at each of these files and folders:

| File/Folder     | Description                                                                             |
| --------------- | --------------------------------------------------------------------------------------- |
| `assets`        | This folder contains all of the images and stylesheets that we will use in our website. |
| `assets/images` | This folder contains all of the images that we will use in our website.                 |
| `assets/styles` | This folder contains all of the stylesheets that we will use in our website.            |
| `.gitignore`    | This file tells Git which files and folders to ignore.                                  |
| `LICENSE`       | This file contains the license for the project.                                         |
| `index.html`    | This is the HTML file that contains the content of our website.                         |

## Installing VS Code and opening the project

Now that we know a little bit about HTML, let's actually start coding. We'll be using a text editor called [Visual Studio Code](https://code.visualstudio.com/). You can download it via Self Service - if you need help installing it, please let me know.

Once you've installed Visual Studio Code, open it up. Now that we've cloned the repository, we can open the project in VS Code. To do this, open VS Code and click on the `File` menu. Then, click on `Open Folder...`. Navigate to the `website-starter` folder and click `Open`.

If you're using VS Code for the first time, you might see a welcome screen. You can close this by clicking on the `Close` button. You should now see the `website-starter` folder in the Explorer pane on the left.

## A little task for you

Post a screenshot of your VS Code window in the support chat. Make sure to include the `website-starter` folder in the screenshot. We're excited to see what you're working on! 🚀

Now, [we can start coding!](../Section_1/Lesson_0_Intro_to_HTML.md) 🎉
