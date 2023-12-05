Use this one
[react project template](https://github.com/goitacademy/react-homework-template#readme)
as a starting point for your program.

# Acceptance criteria

- Created repository `goit-react-hw-08-phonebook`
- When submitting homework, there is a link: to the source files and the work
  page project on `GitHub Pages`
- There are no errors and warnings in the console when running the task code.
- For each component there is a separate folder with the React component file
  and the file styles
- `propTypes` are described for components

## Contact book

Add the ability to register, login, and update to the "Contact Book" program
user, as well as working with a private collection of contacts.

### Backend

There is a ready-made backend for this task. Read the documentation. He supports
all necessary operations with a collection of contacts, as well as registration,
login and update user using JWT. Use it instead of your backend created through
the mockapi.io service.

ser with a form

- `/contacts` – a private route for working with the user's contact collection

Add a navigation component `<Navigation>` with links to navigate to routes

### User menu

Create a `<UserMenu>` component that displays the user's mail and a logout
button account. Here's what its markup might look like.

<div>
  <p>mango@mail.com</p>
  <button>Logout</button>
</div>

### Stylization

This is the final version of the program, so work on the design of the
interface. You can use a styling or component library, for example
[Chakra UI](https://chakra-ui.com/) or [Material-UI](https://material-ui.com/).

---

npm install styled-components@5.3.10

import styled from 'styled-components';

---

npm i react-redux

import { Provider } from 'react-redux'

---

npm i redux-persist

import { PersistGate } from 'redux-persist/es/integration/react'

---

npm i @reduxjs/toolkit

npm install redux

npm install @redux-devtools/extension

npm i axios

---

URL

https://connections-api.herokuapp.com/
