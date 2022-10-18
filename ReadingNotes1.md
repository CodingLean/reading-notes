## What is a “component”?

- A component is a portion of code that describes a well-defined function designed to be flexible and reusable and used as a part of a higher-level interface. They work in conjunction with other components to define a larger functionality.

## What are the characteristics of a component?

- Components are:

reusable – can be reused in various tasks
replaceable – can be replaced with similar components
context-free – not limited to one environment or task
extensible – can have extended features from other components for new behaviors
encapsulated – does not expose internal process, data or state
independent – little to no dependencies on other components

## What are the advantages of using component-based architecture?

- There are many advantages of using component-based architecture such as the ease of deployment, lowered costs, and reliability. This is because components allow us to organize code in an effective way, allowing us to reuse code or modify certain elements without affecting the system as a whole.

## What is “props” short for?

- Props is short for properties.

## How are props used in React?

- Props are assigned much like attributes and values with HTML tags. <ChildComponent text={"I'm the 1st child"} />

## When writing the function, props can be passed as function arguments and accessed with dot notation.

 const ChildComponent = (props) => {
   return <p>{props.text}</p>;
 }
## What is the flow of props?

- Props move in a uni-directional flow from parent to child.

