# React Notes

### Methods for reference

* Here is a list of some of the main lifecycle methods: 

```
componentWillMount() componentDidMount() shouldComponentUpdate() componentDidUpdate() componentWillUnmount() 
```

------------------

### Tips

* It's considered a best practice to set propTypes when you know the type of ` a prop ahead of time.

`MyComponent.propTypes = { handleClick: PropTypes.func.isRequired }`
`Items.propTypes = {quantity: PropTypes.number.isRequired}`

Note: As of React v15.5.0, PropTypes is imported independently from React, like this: import PropTypes from 'prop-types';

------------------

### Theory
* A stateless functional component is any function you write which accepts props and returns JSX.
* A stateless component, on the other hand, is a class that extends React.Component, but does not use internal state
* A stateful component is a class component that does maintain its own internal state. You may see stateful components referred to simply as components or React components.


