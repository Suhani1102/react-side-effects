# react-useEffect
To learn react side effects.

# 1. useEffect: <br/>
**Syntax** : useEffect(() => {...}, [dependency]); <br/>

This react hook requires two arguments: <br/>
1) A function that should be executed after every component evaluation if the specified dependencies changed. <br/>
2) Dependcies of useEffect - the function only runs if the dependencies changed.

# 2. useReducer: <br/>

**Syntax** : const [state, dispatch] = useReducer(reducer, initialArg, init); <br/>

An alternative to useState. <br/>
It helps us to manage complex states which are inter connected.

# useState vs useReducer <br/>

**useState**: It is the main state managment tool. Great for independent pieces of state/data. <br/>

**useReducer**: It's a good option if you need more power. Should be considered if you have related pieces of state/data. Can be helpful if you have more complex state updates.

# 3.React Context API: <br/>

props for configuration and context for state management across components or entire app.

**Context Limitations:**
1. React Context is **not optimized** for high frequency changes.
2. It **shouldn't be used to replace all** component communications and props.
