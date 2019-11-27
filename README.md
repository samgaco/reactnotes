# reactnotes
Notes on react


* It's considered a best practice to set propTypes when you know the type of ` a prop ahead of time.

`MyComponent.propTypes = { handleClick: PropTypes.func.isRequired }`
`Items.propTypes = {quantity: PropTypes.number.isRequired}`

Note: As of React v15.5.0, PropTypes is imported independently from React, like this: import PropTypes from 'prop-types';


