# React JS

## What is React JS?

React is a Javascript library for building user interfaces. 

- **Component-Based:** Build encapsulated components that manage their own state, then compose them to make complex UIs. Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep the state out of the DOM.
- **Learn Once, Write Anywhere:** We don't make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code. React can also render on the server using [Node](https://nodejs.org/en) and power mobile apps using [React Native](https://reactnative.dev/).

---

## How to Install React JS?

### Prerequisite

- Have a code editor like [Visual Studio Code](https://code.visualstudio.com/) or other good code editors.
- Have Node installed. You can download it from [Node.js official website](https://nodejs.org/).
- Have Git installed.
- Have knowledge about Javascript language. 
- Have basic knowledge of React.

### Step-by-Step Installation

1. **Clone the repository**
- Open your web browser and navigate to the GitHub repository page for the React app.
- On the right-hand side of the page, click on the “Code” button.
- In the drop-down menu, select HTTPS to clone the repository.
- Click the “Copy” button to copy the URL of the repository to your clipboard.

Open the terminal and navigate to the directory where you want to store the React project. Then, run the following command to clone the repository:
```bash
git clone https://github.com/<"username">/<"repo-name">.git
```
**Note:** Replace <"username"> with the username of the user who owns the repository, and the <"repo-name"> with the name of the repository.

2. **Navigate to the project directory**
- After the repository is cloned, navigate to the project directory using the following command: 
```bash
cd <repo-name>
```

3. **Install Required Dependencies**
- Once you’re inside the project directory, run the following command to install the dependencies required for the project:
```bash 
npm i
```
This command will read the package.json file in the repository and download all of the dependencies listed there.

In case of issues shown after the npm install, run the below to automatically fix the issues:
```bash
npm audit fix
```

4. **Start the Development Server**
Use this command in terminal:
```bash
npm start
```
This command will start a local development server and run the React project in your web browser. You can access the project by navigating to http://localhost:3000 in your web browser.

That’s it! You should now be able to download and run a React project from Github on your PC.
