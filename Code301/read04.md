# **React and Forms**

<img src="https://reactjs.org/logo-og.png" width="200">

**Q: What is a ‘Controlled Component’?**

**A:** An input form element that a React component renders and controls what happens in that form on subsequent user input

**Q: Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

**A:** as soon as they enter them, because setState() automatically merges a partial state into the current state, we only needed to call it with the changed parts.

**Q: How do we target what the user is entering if we have an event handler on an input field?**

**A:**

```javascript
  handleChange(event) {
    this.setState({value: event.target.value});
  }
```

**Q: Why would we use a ternary operator?**

**A:** faster coding , more readable code

**Q: Rewrite the following statement using a ternary statement:**

**A:**

```Javascript
 if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

  console.log((x===y) ? true : false)
```

**Q: What is the big difference between props and state?**

**A:** props are passed from the parent component to the child, while the state belongs to the component and handled internally

**Q: When do we re-render our application?**

**A:** when the setState() function is called

**Q: What are some examples of things that we could store in state?**

**A:** Javascript Objects and functions
