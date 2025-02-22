# SENG-LIVE-082922 Phase 2 - React

## Phase Level Objectives

- Design a React component hierarchy based on a wireframe
- Use React to create components that interact with an API
- Incorporate client-side routing into a single-page application in React


| Lecture | Notes | Videos | Starter | Solution |
| ------- | :---: | ------ | ------- | -------- |
| 1. (09/19/22) Components & Props     |  [Notes](https://docs.google.com/document/d/1PaEUsoVruIU3pSUOz9jlsfVhxrwB1N7XPYbmak03wKg/edit?usp=sharing)     |  [Video](https://vimeo.com/751431437)      |    [Starter](https://github.com/learn-co-students/SENG-LIVE-082922-phase-2-react/tree/main/01_components_and_props)     |   [Solution](https://github.com/learn-co-students/SENG-LIVE-082922-phase-2-react/commit/b4808295a46edee28d658951481fec708f708704)       |
| 2. (09/20/22) State & Events     |  [Notes](https://docs.google.com/document/d/1PaEUsoVruIU3pSUOz9jlsfVhxrwB1N7XPYbmak03wKg/edit?usp=sharing)     |   [Video](https://vimeo.com/751865683)     |    [Starter](https://github.com/learn-co-students/SENG-LIVE-082922-phase-2-react/tree/main/02_state_and_events%20)     |    [Solution](https://github.com/learn-co-students/SENG-LIVE-082922-phase-2-react/commit/ca9fc639aa4753d7dffb608e38f5615fb72fb848), [Local variables vs state variables](https://codesandbox.io/s/counter-state-example-0r8stb?file=/src/App.js), [SmartHome app - Passing State as Props](https://codesandbox.io/s/vigilant-minsky-iiykrb)      |
| 3. (09/21/22) Information Flow     |  [Notes](https://docs.google.com/document/d/1PaEUsoVruIU3pSUOz9jlsfVhxrwB1N7XPYbmak03wKg/edit?usp=sharing)     |  [Video](https://vimeo.com/752290334)      |   [Starter](https://github.com/learn-co-students/SENG-LIVE-082922-phase-2-react/tree/main/03_information_flow)      |    [Solution](https://github.com/learn-co-students/SENG-LIVE-082922-phase-2-react/commit/7517a70b8b6e295722fd7f544e43343507c2dd4b), [SmartHome app with individually clickable bulbs](https://codesandbox.io/s/smarthome-app-to-add-inverse-data-flow-xrbf4r?file=/src/LightBulb.js)      |
| 4. (09/23/22) Forms     |   [Notes](https://docs.google.com/document/d/1PaEUsoVruIU3pSUOz9jlsfVhxrwB1N7XPYbmak03wKg/edit?usp=sharing)    |   [Video](https://vimeo.com/753123181)     |   [Starter](https://github.com/learn-co-students/SENG-LIVE-082922-phase-2-react/tree/main/04_react_forms)      |  [Solution](https://github.com/learn-co-students/SENG-LIVE-082922-phase-2-react/commit/dd86f3e3baa2d3f6f29c8f6d532ae444a0171829), [controlled form with single state object](https://codesandbox.io/s/controlled-form-with-formstate-object-080822-58jlp5?file=/src/App.js:815-893), [controlled form with individual pieces of state](https://codesandbox.io/s/controlled-form-with-individual-pieces-of-state-pbjpe4?from-embed)        |
| 5. (09/26/22) Side Effects & Data Fetching     |  [Notes](https://docs.google.com/document/d/1PaEUsoVruIU3pSUOz9jlsfVhxrwB1N7XPYbmak03wKg/edit?usp=sharing)     |   [Video](https://vimeo.com/754010233)     |   [Starter](https://github.com/learn-co-students/SENG-LIVE-082922-phase-2-react/tree/main/05_side_effects_and_data_fetching)      |   [Solution](https://github.com/learn-co-students/SENG-LIVE-082922-phase-2-react/commit/ed42551658ab2c3daf17b6596d4aac3adbf12555), [useEffect cleanup demo](https://codesandbox.io/s/useeffect-cleanup-ig17kd?file=/src/Timer.js)       |
| 6. (09/27/22) PATCH & DELETE     |   [Notes](https://docs.google.com/document/d/1PaEUsoVruIU3pSUOz9jlsfVhxrwB1N7XPYbmak03wKg/edit?usp=sharing)    |   [Video](https://vimeo.com/754451357)     |    [Starter](https://github.com/learn-co-students/SENG-LIVE-082922-phase-2-react/tree/main/06_PATCH_DELETE)     |   [Solution](https://github.com/learn-co-students/SENG-LIVE-082922-phase-2-react/compare/main...06_solution)       |
| 7. (09/30/22) Client-Side Routing     |   [Notes](https://docs.google.com/document/d/1PaEUsoVruIU3pSUOz9jlsfVhxrwB1N7XPYbmak03wKg/edit?usp=sharing)    |    [Video](#)    |   [Starter](#)      |    [Solution](#)      |


## 1: Components and Props
### SWBATs:
- Review the benefits of React over Vanilla JS 
- Review the difference between HTML and JSX
- Review the importance of Components
- Review how a component is written
- Explain what props are and how to create them
- Recognize best practices when writing components and props
- Observe how to render multiple components from a list
### Lecture Topics:
- JSX
- Components
- Props
- Destructuring


## 2: State & Events

### SWBATs:
- Explain the importance of state
- Explain the difference between state and props
- Observe how to use the useState hook
- Observe how to use DOM events in React
### Lecture Topics:
- Creating & Updating State
- Events
- Callbacks
- useState


## 3: Information Flow
### SWBATs:
- Define the term “lifting state”
- Recognize the pattern for changing state in a parent component from a child component
- Explain the role that callback functions play in changing parent state
- Observe how we can render reusable components that invoke different callback functions after an event
- Recognize destructured props and how to work with them
### Lecture Topics:
- Callback functions as props
- Changing parent state
- Reusing components w/ different behaviors

## 4: Forms
### SWBATs:
- Explain the difference between a controlled and uncontrolled input
- Explain why controlled inputs are preferred by the React community
- Review how to use callback functions with events in React
- Review how to change parent state from a child component
### Lecture Topics:
- Controlled vs uncontrolled inputs
- Forms

## 5: Side Effects & Data Fetching

### SWBATs:
- Explain what a side effect is
- Observe how React manages side effects with the useEffect hook
- Observe how to use the useEffect hook to fetch data on page load
- Observe how to send a POST request via form
- Review changing parent state
### Lecture Topics:
- useEffect
- Dependency array
- fetch => GET & POST

## 6: PATCH & DELETE
### SWBATs:
- Observe how to send a PATCH & DELETE request
- Review changing parent state
### Lecture Topics:
- fetch => PATCH & DELETE

## 7: Client Side Routing

### SWBATs:
- Review the difference between server-side and client-side routing
- Observe a refactor to include client-side routing using React Router V5
- Explain what a nested route is
- Observe how to handle nested client-side routes 
### Lecture Topics:
- React Router

