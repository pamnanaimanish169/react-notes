# What is JSX?

JSX stands for JavaScript XML and is a language designed to help write JavaScript code in React.

# What is React?

React is a JavaScript library(not a framework like Angular) to develope Single Page Applications.

# What is the difference between React & Angular?

React is a JavaScript Library to develop Single Page Applications(SPA) while Angular is a JavaScript framework to develop Single Page Applications.

React only supports one-way binding while Angular supports two-way binding(Source to data , data to source).

React uses virtual DOM(Document Object Model) while Angular uses real DOM(Document Object Model).

# Explain the concept of components in React.

Components are the building blocks of React. Components are nothing but different parts of a Application which are required to run it. There are two types of components in React:

- Functional based components
- Class based components


Functional based components are nothing but functions inside a React file:
  
```
    function App() {
    return (
        <div>
        <h2> Let's get strated! </h2>
        <ExpenseItem></ExpenseItem>
        </div>
    );
    }
```

Here App() is a function inside which we write our JSX(JavaScript XML) code.

Class based components are components where we render Components instead of functions like this:

```
class App extends React.Component {
        render() {
            return <h1>GeeksForGeeks</h1>;
        }
    }
```

    

Here a class named App is rendered instead of a function, but in both cases App is exported(or any other name).

# How do you get started in React & what version are you using to learn React?

To get started in React, you need to install a package named ```create-react-app``` from npmjs.com by using the following command:

```
npm i create-react-app
```

then you need to create a sample project to write some code:

```
npx create-react-app my-app
```

This will create a application named my-app in your folder where you run this command. Now you need to go to the application that you have created:

```
cd my-app
```

and then you need to run the follwoing code:

```
npm run start
```

Happy coding!

The version we are using is 17.0.2

```
"react": "^17.0.2",
"react-dom": "^17.0.2",
```
