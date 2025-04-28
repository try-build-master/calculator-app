
# Backend (Node.js + Express)

Welcome to the backend of the **Calculator App**! 🎉  
In this section, you will work on the backend using **Node.js** and **Express** to build an API that handles basic arithmetic calculations.

---

## 🛠 Structure
- **`server.js`**: Main entry point of the application. Here, the Express app is initialized and API routes are defined.
- **`package.json`**: Manages backend dependencies and scripts.
- **`README.md`**: Explains the tasks and steps for backend development.

---

## 🚀 Tasks

### 1. `backend-basic`
- Set up an Express server.
- Create a basic **`/calculate`** route.
- The route should **accept JSON data** with two numbers and an operator (`+, -, *, /`) but **without logic**.

### 2. `backend-logic`
- Implement the **calculation logic** for the `/calculate` endpoint.
- Accept the operator and numbers from the request body and return the result.

### 3. `add-backend-tests`
- Use **Jest** or a similar testing framework to write unit tests for your `/calculate` API.
- Make sure to test various edge cases (e.g., division by zero).

---

## 🔧 Running the Backend

1. Install dependencies:
   ```bash
   npm install
2. Start the backend server:
    ```bash
    npm run dev
The server will run on http://localhost:5000.
