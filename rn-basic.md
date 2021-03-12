# React Native Quick Intro

---

### what is react 

- react is js library for building UI
- key concept in React: component
- A component is a piece of UI
- components are composable & resuable 
- components can consist of other components and of primitives


### what is react native

- way/ framwork to build moblie app using React & java sceipt

### How does it work

- 2 importmant thread runing in RN app
	1. main thread in standard native app -> handles displaying the elements of the UI and processs user gestures
	2. the other thread for RN -> execute JS code in sparate JS engine -> deals with bussiness logic of the app / defines the structure & funtion of the UI
- 2 threads never comunicate directly & never block each other

### how threads interact

- core RN -> bridge
- async -> not block each other 
- serializable
- batched -> transfer msg in an optimized way

### RN concepts
- JSX
- components
- state 
- props

### Hello word Example

