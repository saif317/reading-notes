# **State and Props**

<img src="https://reactjs.org/logo-og.png" width="200">

**Q: What does .map() return?**

**A:** the augmented array

**Q: If I want to loop through an array and display each value in JSX, how do I do that in React?**

**A:**

```HTML
<div className="users">
    {users.map((user, index) => (
        <div key={index}>
            <h3>{user.name}</h3>
            <p>{user.location}</p>
            <p>{user.car}</p>
        </div>
    ))}
</div>
```

> -- <cite>[Loop Over and Display Data with JSX][1]</cite>

[1]: https://scotch.io/courses/10-react-challenges-beginner/loop-over-and-display-data-with-jsx

**Q: Each list item needs a unique \_\_\_\_**

**A:** Key

**Q: What is the purpose of a key?**

**A:** to identify which items have changed

**Q: What is the spread operator?**

**A:** an operator that spread the values of an array into seperate values which can be passed into a function

**Q: List 4 things that the spread operator can do**

**A:** pass values of an array into a function - combine arrays - pass all key:value pairs from an object - copy an array

**Q: Give an example of using the spread operator to combine two arrays.**

**A:**

```Javascript
let arr1 = [0, 1, 2];
let arr2 = [3, 4, 5];

arr1 = [...arr2, ...arr1];
```

> -- <cite>[Loop Over and Display Data with JSX][2]</cite>

[2]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax

**Q: Give an example of using the spread operator to add a new item to an array.**

**A:**

```Javascript
[...iterableObj, '4', 'five', 6];
```

> -- <cite>[Loop Over and Display Data with JSX][3]</cite>

[3]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax

**Q: Give an example of using the spread operator to combine two objects into one.**

**A:**

```Javascript
let obj1 = { foo: 'bar', x: 42 };
let obj2 = { foo: 'baz', y: 13 };

let mergedObj = { ...obj1, ...obj2 };
// Object { foo: "baz", x: 42, y: 13 }
```

> -- <cite>[Loop Over and Display Data with JSX][4]</cite>

[4]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax

**Q: what is the first step that the developer does to pass functions between components?**

**A:** Create the function

**Q: In your own words, what does the increment function do?**

**A:** Changes the state of the component

**Q: How can you pass a method from a parent component into a child component?**

**A:** by passing it as a prop

**Q: How does the child component invoke a method that was passed to it from a parent component?**

**A:** this.props.increment(this.props.name)
