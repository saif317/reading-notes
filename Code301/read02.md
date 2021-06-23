# **State and Props**

<img src="https://reactjs.org/logo-og.png" width="200">

**Q: what happens first, the ‘render’ or the ‘componentDidMount’?**

**A:** render

**Q: What is the very first thing to happen in the lifecycle of React?**

**A:** calling the constructor of the react component

**Q: Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates**

**A:** constructor - render - React Updates - componentDidMount - componentWillUnmount

**Q: What does componentDidMount do?**

**A:** clean up the DOM and netwrok requests

**Q: What types of things can you pass in the props?**

**A:** Javascript Objects and functions

**Q: What is the big difference between props and state?**

**A:** props are passed from the parent component to the child, while the state belongs to the component and handled internally

**Q: When do we re-render our application?**

**A:** when the setState() function is called

**Q: What are some examples of things that we could store in state?**

**A:** Javascript Objects and functions
