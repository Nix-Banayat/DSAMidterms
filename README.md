# React JS

---

## What do you want to know?

1. [What is React JS?](#what-is-react-js)
2. [How to Install React JS](#how-to-install-react-js)
3. [Why Learn React JS?](#why-learn-react-js)
4. [Features of React JS](#features-of-react-js)
5. [React Tutorial Videos and Links](#react-tutorial-videos-and-links)

---

## What is React JS?

React is a Javascript library for building user interfaces. It is developed by Facebook. It simplifies creating dynamic and interactive web apps with the help of component-based architecture, reusability, and efficient rendering with the JSX and virtualDOM.

- **Component-Based:** Build encapsulated components that manage their own state, then compose them to make complex UIs. Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep the state out of the DOM.
- **Learn Once, Write Anywhere:** We don't make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code. React can also render on the server using [Node](https://nodejs.org/en) and power mobile apps using [React Native](https://reactnative.dev/).

---

## How to Install React JS?

### Prerequisite

- Have a code editor like [Visual Studio Code](https://code.visualstudio.com/) or other good code editors.
- Have Node installed. You can download it from [Node.js official website](https://nodejs.org/).
- Have Git installed. You can download it from [Git official website](https://git-scm.com/).
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

---

## Why Learn React JS?

- Once you learn its concepts, you can use React across various platforms to build quality user interfaces.
- React provides a great developer experience, making it easier to understand and write code.
- React has a broad community, excellent performance, and ease of testing, making it an ideal choice for web development. 

---

## Features of React JS.

1. **JSX (Javascript Syntax Extension)**
- JSX combines HTML and JavaScript, allowing you to embed JavaScript objects within HTML elements. It enhances code clarity and simplifies UI development.

**Example:**
```jsx
const name = "Nix";
const ele = <h1>Welcome {name}</h1>
```

2. **Virtual DOM (Document Object Model)**
- It uses a Virtual DOM, which is an exact copy of Real DOM. 
- When there are modifications in the web application, React updates the virtual DOM first and then computes the differences between the real DOM and the virtual DOM. This minimizes unnecessary re-rendering and improves performance.

<img src='https://miro.medium.com/v2/resize:fit:1400/1*MVVai4SRxxuy7xdwRH9Yww.jpeg' width='600'>

3. **One-way Data Binding** 
- Data flows from parent components to child components. Child components cannot directly modify parent states but can communicate to request changes.

4. **Performance**
- The Virtual DOM and component-based architecture contribute to improved performance with faster execution and effective rendering.

5. **Extension**
- React has a rich ecosystem and supports various extensions and tools such as **Flux**, **Redux**, and **React Native**.

6. **Conditional Rendering**
- JSX allows writing conditional statements directly.
- Displays data in the browser based on previous conditions.

**Example:**
```jsx
const student = 60;
if (student >= 50){
    return <p>Greater than {student}</p>;
} else {
    return <p>{student}</p>;
}
```

7. **Components**
- React divides web pages into reusable and immutable components.   
- Component-based development simplifies code organization and maintenance.

---

## React Tutorial Videos and Links

- All about React JS - [React Documentation](https://react.dev/).
- How to Install React JS & Set up Your First Project - [Set Up Your React JS](https://www.youtube.com/watch?v=av5fmpgEJSU&ab_channel=RishavChanda).
- Creating React App Link - [Create React App Documentation](https://create-react-app.dev/docs/getting-started/).