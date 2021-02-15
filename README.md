```
Create .env
    NODE_ENV = "if development or production"
    PORT = "port here"
    MONGO_URI = mongodb+srv://eckzen:<password>@cluster0.ssawl.mongodb.net/<dbname>?retryWrites=true&w=majority

Redux
install redux devtool
$npm i redux react-redux redux-thunk redux-devtools-extension
store.js
- redux
    - createStore
    - combineReducers
    - applyMiddleware
- redux-thunk
    - thunk
- redux-devtools-extension
    - composeWithDevTools

Redux Flow
    Start with the constants
    Create a reducer
    Add the reducer to the Store
    Create Action
    Go to the UI implement
        import useDispatch,useSelector
        useDispatch
        import Actions
        dispatch an Action
        useSelector to get the state
        useSelector state thru reducer from the store
        destructure the state fron useSelector

The Project Flow is:
- Create the backend route
- Create the Constants
- Create the reducers
- Create the action
- Create the screen
- Bring the action in and call it
- Get what we want in the state
```
