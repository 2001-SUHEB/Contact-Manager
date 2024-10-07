 # Contact Manager React App

Welcome to the **Contact Manager** application! This project showcases essential React concepts like **components**, **hooks**, **API fetching**, and integrates a **JSON Server** for performing **CRUD operations** on contact data.

This app is designed to be a comprehensive learning tool for engineers who want hands-on experience with React and its core features. It also provides an easy-to-use setup with a mock backend using JSON Server, making it a complete package for practicing full-stack development.

## Overview

- **Frontend:** React, React Hooks, CSS
- **Backend:** JSON Server (Mock API)
- **API Integration:** REST API for performing CRUD operations on contacts

## Project Features

### 1. React Components
   - Reusable and modular components, including `ContactList`, `AddContact`, `EditContact`, and `ContactDetail`. These components are designed to handle UI rendering and state management cleanly.

### 2. React Hooks
   - **State Management:** React's `useState` is used to manage local state, handling the addition and updating of contacts.
   - **Side Effects:** `useEffect` is used to fetch contacts from the JSON Server when the component is mounted.
   - **Custom Hooks:** Custom hooks help reduce repetitive logic, making the code cleaner and more efficient.

### 3. CRUD Operations
   - **Create:** Add new contacts via the `AddContact` component using a POST request to the JSON server.
   - **Read:** Fetch and display contacts from the backend using a GET request.
   - **Update:** Modify existing contact details via the `EditContact` component using PUT requests.
   - **Delete:** Remove contacts by sending DELETE requests to the server.

### 4. API Fetching
   - The app interacts with the backend (JSON Server) via `fetch` or `axios` to perform asynchronous data operations.
   - Both error handling and loading states are considered to ensure a smooth user experience.

### 5. Routing
   - Client-side routing is handled by `react-router-dom`, enabling navigation between different pages without refreshing the entire app.
   - Routes include:
     - `/` - Contact List
     - `/add` - Add a new contact
     - `/edit/:id` - Edit an existing contact
     - `/contact/:id` - View contact details

## Tech Stack

- **Frontend:**
  - React (with Hooks)
  - CSS
  - React Router

- **Backend:**
  - JSON Server (mock backend to simulate API endpoints)

## Contribution

Feel free to contribute to this project by submitting a pull request. Contributions can include improving the frontend, adding more features, or enhancing the backend functionality.

---

**Developed by Syed Sha Suheb, Software Engineer**

This project is a great starting point for anyone learning React or full-stack development with mock APIs. Clone, modify, and extend the application to build your own variations!
