# react-useEffect
To learn react side effects.

# 1. useEffect: <br/>
Syntax : useEffect(() => {...}, [dependency]); <br/>

This react hook requires two arguments: <br/>
1) A function that should be executed after every component evaluation if the specified dependencies changed. <br/>
2) Dependcies of useEffect - the function only runs if the dependencies changed.

# 2. useReducer: <br/>

Syntax : const [state, dispatch] = useReducer(reducer, initialArg, init); <br/>

An alternative to useState. <br/>
It helps us to manage complex states which are inter connected.

# useState vs useReducer <br/>
