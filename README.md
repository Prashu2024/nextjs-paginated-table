# Next.js Table with Pagination

This project is a Next.js application that fetches user data from the [Reqres API](https://reqres.in/api/users?page=1), displays the users in a table with pagination, and allows dynamic navigation between pages. The project is set up for deployment on Vercel.

## Features

- **Data Fetching:** Uses Axios to fetch user data from the Reqres API.
- **Table Display:** Renders user details (ID, Email, First Name, Last Name, Avatar) in a table.
- **Pagination:** Enables navigation between pages dynamically based on the API response.
- **Deployment Ready:** Easily deploy your project to Vercel.

## Getting Started

Follow these steps to set up the project locally.

### Prerequisites

- [Node.js](https://nodejs.org/en/) (v12 or later)
- npm (comes with Node.js) or yarn

### Installation

1. **Create the Next.js project and install dependencies:**

   ```bash
   npx create-next-app@latest nextjs-table-pagination
   cd nextjs-table-pagination

2. Install Axios:

    ```bash
    npm install axios

2. Project Structure:

The main code for fetching data and rendering the table is in the app directory (e.g., app/page.js). You can modify this file to suit your design and functionality needs.

### Running the Project
   To run the project locally:
   ```bash
    npm run dev
    
Open http://localhost:3000 in your browser to see the application in action.
