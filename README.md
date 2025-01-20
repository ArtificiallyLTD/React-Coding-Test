# React.js Coding Test for Artificially

Welcome to the second stage of our recruitment process at **Artificially**! This test is designed to assess your proficiency in **React.js**, focusing on building a frontend application that interacts with APIs, handles state management, and ensures proper file handling.

Our website: [artificially.io](https://artificially.io)

---

## Objective

You are tasked with building a **File Management Frontend** that interacts with a backend API. This frontend should allow users to upload, view, download, and delete files through the provided API.

---

## Requirements

### 1. Features

1. **File Listing**
   - Display a list of files retrieved from the API.
   - Show each file’s:
     - Name.
     - Upload date.
     - Action buttons (e.g., download and delete).

2. **File Upload**
   - Provide a form to upload files.
   - Validate file input before sending it to the API.

3. **File Actions**
   - **Download**: Allow users to download files by triggering the corresponding API endpoint.
   - **Delete**: Allow users to delete files with a confirmation dialog.

4. **State Management**
   - Use React’s **useState** and **useEffect** hooks (or **React Query** if preferred).
   - Ensure the UI updates dynamically after file actions (e.g., upload, delete).

5. **Error Handling**
   - Display error messages for failed uploads, invalid files, or API errors.
   - Provide a fallback message if no files are available.

---

## Instructions

1. **Clone the Repository**
   Clone this repository to your local environment:
   ```bash
   git clone git@github.com:ArtificiallyLTD/React-Coding-Test.git
   cd React-Coding-Test
   ```

2. **Set Up the Project**  
   1. Install dependencies:
      ```bash
      npm install
      ```
   2. Start the development server:
      ```bash
      npm start
      ```

3. **Connect to the API**  
   - The backend API will be provided separately.
   - Update the base URL for API requests in a centralized configuration file (e.g., \`src/config/api.js\`):
     ```javascript
     export const API_BASE_URL = "http://your-backend-api-url";
     ```

4. **Build the Application**  
   - Implement the required features and functionality in React.js.
   - Use a UI library (e.g., Material-UI, TailwindCSS) or custom styles as you prefer.

5. **Submit Your Work**  
   - Push your code to a **private GitHub repository**.
   - Invite the following reviewers to your repo:
     - `contact@artificially.io`

---

## Evaluation Criteria

Your submission will be evaluated based on:

1. **Code Quality**
   - Clean and modular components.
   - Proper state management and API handling.
   - Well-structured file organization.

2. **Functionality**
   - Completeness of required features (list, upload, download, delete).
   - Dynamic updates after file actions.

3. **Error Handling**
   - Graceful handling of API errors and edge cases.

4. **User Interface**
   - A simple, clean, and intuitive UI.

5. **Documentation**
   - Clear setup and usage instructions in `README.md`.