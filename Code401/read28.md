# Component lifecycle

## Why do we not need more .html pages in a multi-page React app?

because all the components get rendered in the index.html page

## If we wanted a component to show up on every page, where would we put it and why?

Inside the <BrowserRouter />, outside a <Route /> so React doesnt consider it a route

## What does routing do with the components that were rendered when a new route is requested

it gets unmounted and removed from the dom

## What does props.children contain?

whatever is in between the opening and closing tags when invoking a component

## How do useState() and this.setState() differ?

useState if for functional components this.setState() is for class componenets

## State Hook

a special function that lets you “hook into” React features

## Mounting and Un-Mounting

adding and removing the component from the Dom
