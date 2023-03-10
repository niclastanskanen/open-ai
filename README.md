# Open Ai

### Communication with advanced GPT3 model API.
The OpenAi app is designed to have a similar elegant user interface as ChatGPT, which communicates with advanced GPT3 model APIs. AI can be asked for assistance in JavaScript, React, or any other programming language by providing code and translating it.

## -> [Live Site](https://open-ai-psi.vercel.app/) <- :computer:

## -> [Live Server](https://open-ai-ttfo.onrender.com/) <- :file_folder:

[Error Code 429 - Rate limit reached for requests](https://help.openai.com/en/articles/6891829-error-code-429-rate-limit-reached-for-requests)

![React](https://skillicons.dev/icons?i=js,vite,nodejs)

![OpenAI](https://a11ybadges.com/badge?logo=openai)

## Table of Contents

- [User Experience (UX)](#user-experience-ux)
  - [Design](#design)
    - [Color Scheme](#color-scheme)
    - [Typography](#typography)
- [Features](#features)
  - [Home Page](#home-page)
  - [Server Page](#server-page)
- [Testing](#testing)
  - [Bugs](#bugs)
    - [Fixed Bugs](#fixed-bugs)
    - [Remaining Bugs](#remaining-bugs)
- [Technologies Used](#technologies-used)
  - [Languages and Frameworks Used](#languages-and-frameworks-used)
  - [Node Packages / Dependencies Used](#node-packages--dependencies-used)
  - [Programs and Tools Used](#programs-and-tools-used)
- [Deployment](#deployment)
  - [Forking the GitHub Repository](#forking-the-github-repository)
  - [Making a Local Clone](#making-a-local-clone)
- [Credits](#credits)
  - [Acknowledgments](#acknowledgments)


## User Experience UX

### Color-scheme
<img src ="./docs/images/color-scheme.png">

### Typography

[Alegreya Sans, sans-serif](https://fonts.googleapis.com/css2?family=Alegreya+Sans:wght@100;300;400;500;700;800;900&display=swap)

<hr>

## Features

### Home Page

<img src="./docs/images/homapage.png">

### Server Page

<img src="./docs/images/server.png">

<hr>

## Testing

## Bugs
### Fixed Bugs

#### Error code 5000
<img src="./docs/images/bug-port-5000.png">
<img src="./docs/images/bug-port-5000-solution.png">
<img src="./docs/images/bug-port-5000-fix.png">


#### Typo
OPENAI_API_KEY instead of OPEN_API_KEY
<img src="./docs/images/bug-typo-api.png">
<hr>

#### Typo
text.charAt instead of chartAt

<img src="./docs/images/bug-typo.png">



### Remaining Bugs
[Error Code 429 - Rate limit reached for requests](https://help.openai.com/en/articles/6891829-error-code-429-rate-limit-reached-for-requests)

This error message indicates that you have hit your assigned rate limit for the API. This means that you have submitted too many tokens or requests in a short period of time and have exceeded the number of requests allowed. This could happen for several reasons, such as:

<img src="./docs/images/bug-error-429-homepage.png">

<img src="./docs/images/bug-error-429-response.png">

<hr>

## Technologies Used

### Languages and Frameworks Used
HTML

CSS

JavaScript - https://www.javascript.com/

Vite - https://vitejs.dev/

Node.js https://nodejs.org/


### Node Packages / Dependencies Used
- [Vite](https://vitejs.dev/guide/)
- [Cors](https://www.npmjs.com/package/cors)
- [Dotenv](https://www.npmjs.com/package/dotenv)
- [Express](https://www.npmjs.com/package/express)
- [Nodemon](https://www.npmjs.com/package/nodemon)
- [OpenAI](https://www.npmjs.com/package/openai)

### Programs and Tools Used
- [Open Ai](https://openai.com/)
- [Render](https://render.com/)
- [Vercel](https://vercel.com/)
- [Git](https://git-scm.com/)
- [GitHub](https://github.com/)
- [Visual Studio Code](https://code.visualstudio.com/)

<hr>

## Deployment

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on
our GitHub account to view and/or make changes without affecting the original
repository by using the following steps...

1. Log in to GitHub and locate the [GitHub
   Repository](https://github.com/niclastanskanen/open-ai)
1. At the top of the Repository (not top of page) just above the "Settings"
   Button on the menu, locate the "Fork" Button.
1. Click the button (not the number to the right) and you should now have a copy
   of the original repository in your GitHub account.

### Making a Local Clone

**NOTE**: It is a requirement of the project that you have Python version 3.8 or higher installed locally.

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/niclastanskanen/open-ai).
1. Under the repository name, click "Code".
1. To clone the repository using HTTPS, under "HTTPS", copy the link.
1. Open your local terminal with git installed
1. Change the current working directory to the location where you want the cloned directory to be created.
1. Type `git clone`, and then paste the URL you copied in Step 3.

    ```console
    ~$ git clone https://github.com/niclastanskanen/open-ai
    ```

1. Press Enter. Your local clone will be created.

    ```console
    $ git clone https://github.com/niclastanskanen/open-ai
    > Cloning into `test-dir`...
    > remote: Counting objects: 10, done.
    > remote: Compressing objects: 100% (8/8), done.
    > remove: Total 10 (delta 1), reused 10 (delta 1)
    > Unpacking objects: 100% (10/10), done.
    ```

    [Click here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) for a more detailed explanation of the process above with pictures.

1. Change the current working directory to the cloned project folder (this will be a child directory in the location you cloned the project).

1. This guide assumes you have Node.js and npm installed locally, if this is not the case please install these now.
1. From the terminal run the command `npm install` to install all project dependencies.
1. Run the command `npm run dev` to run the application.

<hr>

## Credits


### Acknowledgments

Adrian for a great support and mentor.

