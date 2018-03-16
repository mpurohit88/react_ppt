#HSLIDE

# React Part 1

<span class="primary"><strong>Mukesh Purohit</strong></span> - 16 March 2018
 

#HSLIDE
Why React ?

React is a view layer that uses virtual DOM for performance.

React can be used as the V in MVC.

React’s true strengths: composition, unidirectional data flow, freedom from DSLs, explicit mutation and static mental model.

#HSLIDE
Components, State and Lifecycle

#HSLIDE
components

components are basically just functions that return the view based on the current state.

Components let you split the UI into independent, reusable pieces, and think about each piece in isolation

single responsibility principle, that is, a component should ideally only do one thing.


#HSLIDE
More About Components

Stateful vs Stateless

Classes and Functions

Pure and Impure

Presentational and Container Components

Composition Patterns

#HSLIDE
Here are two types of “model” data in React:

props and state

#HSLIDE
state

Only components defined as classes can have state.

#HSLIDE
props

props are inputs to a React component. They are data passed down from a parent component to a child component. 

Remember that props are readonly. They should not be modified in any way.

difference between state and props is that props are passed from a parent component, but state is managed by the component itself.

#HSLIDE
Lifecycle Methods

Lifecycle methods are custom functionality that gets executed during the different phases of a component

Where should you make the API calls?

#HSLIDE

Questions ?
#HSLIDE

Thank you
