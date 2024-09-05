# To run API folder - 
> 1.npm install
> 2.npm run dev


## To run client -
> 1.npm install
> 2.Add mongoURI
> 3.npm run dev

### Backend (Node.js + Express)
# Dependencies

> bcryptjs: For hashing passwords.
cookie-parser: Parsing cookies.
dotenv: Environment variables.
express: Web server framework.
jsonwebtoken: Authentication tokens.
mongoose: MongoDB object modeling.
nodemon: Auto-restart on file changes (development).

## Authentication (auth.js)

/register: POST request for user registration.
/login: POST request for user login, generating JWT.
/logout: GET request for user logout (clearing cookies).

#### Todo CRUD (todo.js)

/todos: GET request to fetch all todos.
/todo/:id: GET request to fetch a specific todo.
/add: POST request to add a new todo.
/update/:id: PUT request to update an existing todo.
/delete/:id: DELETE request to delete a todo.

Frontend (React)
# Dependencies

@reduxjs/toolkit: Redux state management.
react: Core React library.
react-dom: React DOM rendering.
react-icons: Icons for UI.
react-redux: Redux bindings for React.
react-router-dom: Routing in React.
redux-persist: Persisting Redux state.
swiper: Optional, for carousel or slider features.

## Authentication Flow

LoginPage.js: Form for login with Redux actions.
RegisterPage.js: Form for registration with Redux actions.
PrivateRoute.js: Higher-order component for authenticated routes.
### Todo Management

TodoList.js: Fetches todos from backend using Redux.
TodoItem.js: Displays each todo item with options to edit or delete.
AddTodoForm.js: Form for adding new todos.
EditTodoForm.js: Form for editing existing todos.
#### Redux State Management

actions/: Redux action creators (e.g., authActions.js, todoActions.js).
reducers/: Redux reducers managing state changes.
store.js: Configures Redux store with middleware (e.g., redux-thunk for async actions, redux-persist for state persistence).
