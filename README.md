# Calculator App

Welcome to the **Calculator App** project! 🎉  
In this project, you'll build a **full-stack calculator application**. It is divided into two main parts:  
- **Backend**: Built with **Node.js** and **Express** to handle calculations.
- **Frontend**: Built with **React** to handle the UI and interact with the backend.

The goal of this project is to give you hands-on experience in building both backend and frontend, connecting them together, and learning key concepts along the way.

---

## 📚 Project Structure
The project is divided into two main folders:
- **`backend/`**: Contains the server-side logic (API for calculation).
- **`frontend/`**: Contains the React application for the UI.

Each folder has its own set of tasks and instructions, and you'll work through each of them, completing progressively more complex tasks.

---

## 🛠 Tech Stack
- **Backend**: 
  - **Node.js**
  - **Express**
- **Frontend**: 
  - **React** (Vite)
- **Database**: None for this project (pure calculation API)

---

## 🏗️ Design Pattern
- **MVC (Model-View-Controller)**: This will be loosely followed for organization purposes.
  - **Model**: Calculation logic (inside backend).
  - **View**: React frontend UI.
  - **Controller**: Express routes handle requests.

---

## 🚀 Project Workflow & Branches

### 1. `starter-setup`  
- Setup project folders and basic files for both backend and frontend.

### 2. `backend-basic`
- Set up a basic **Express server** and **`/calculate` API** endpoint.
- The endpoint will accept numbers and an operator but won’t implement logic yet.

### 3. `frontend-basic`
- Create the basic **React UI**: inputs for numbers, operator, and a button.
- No logic yet, just the structure.

### 4. `backend-logic`
- Implement actual **calculation logic** in the backend for addition, subtraction, multiplication, and division.
- Ensure API returns correct responses.

### 5. `frontend-api-call`
- Connect the **frontend UI** to the backend API.
- Make the **API call** when the user submits the form.

### 6. `frontend-ui-polish`
- Style the frontend to make it **user-friendly**.
- Add basic CSS or styling libraries (e.g., Tailwind, Styled Components).

### 7. `add-backend-tests`
- Write tests for the **backend API** using Jest or another testing library.
- Ensure the backend works properly under various conditions.

### 8. `final-polish`
- Final improvements:
  - Handle errors and edge cases.
  - Refine UX and UI.
  - Optional extra features (e.g., keyboard input, decimal numbers).

---

## 🔧 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/try-build-master/calculator-app.git

2. Install dependencies:
    ```bash
    cd backend && npm install
    cd ../frontend && npm install
3. Run the backend:
    ```bash
    npm run dev
4. Run the frontend:
    ```bash
    npm run dev

The frontend will run on http://localhost:5173 and the backend on http://localhost:5000.


