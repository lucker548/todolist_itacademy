# zustand_todo_list

## Start project
```
npm i
npm run dev
```
Open `http://localhost:3000`



Model-View-Controller (MVC) pattern:

Model: This is your data layer. It's where you'd use Zustand to manage the state of your ToDo List app. With Zustand, you create a store to keep your state, and you can create actions that modify the state.

View: This is the presentation layer, and it's where you'd use React (or another library/framework) to render your UI based on your state.

Controller: In this pattern, the controller mediates between the model and the view. However, in a React app, you usually don't have a distinct controller. Instead, React components themselves act like controllers, responding to user input and updating the model.

