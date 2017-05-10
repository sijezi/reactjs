Why You Should ReactJS
- Simple
- Express how your app should like
- Automatically manage UI update
- Reusable Component
- Declarative Programming


### React Without JSX

```javascript

  ReactDOM.render(
      React.createElement(
        'h1',
        null, // Null means not passing any props to component yet
        'Hello World!'
      ),
      document.getElementById('app')
    );

```
