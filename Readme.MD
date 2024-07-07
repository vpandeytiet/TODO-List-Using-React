# TODO List Application

This is a simple TODO list application developed using React. It allows users to add, delete, and mark tasks as completed.

## Features

- Add new tasks
- Delete tasks
- Mark tasks as completed
- Filter tasks (All, Active, Completed)

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/todo-list-react.git
   cd todo-list-react
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run the application:**

   ```bash
   npm start
   ```

   The application will start on `http://localhost:3000`.

## Deployment

This project can be deployed using GitHub Pages. To deploy the application, follow these steps:

1. **Install the `gh-pages` package as a dev dependency:**

   ```bash
   npm install gh-pages --save-dev
   ```

2. **Add the following `homepage` field in your `package.json` file:**

   ```json
   "homepage": "http://your-username.github.io/todo-list-react"
   ```

3. **Add the following scripts in your `package.json` file:**

   ```json
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d build"
   }
   ```

4. **Deploy the application:**

   ```bash
   npm run deploy
   ```

   The application will be deployed to GitHub Pages.

## Usage

1. **Add a task:**
   - Type your task in the input field and press Enter or click the "Add" button.

2. **Delete a task:**
   - Click the "Delete" button next to the task you want to remove.

3. **Mark a task as completed:**
   - Click the checkbox next to the task to mark it as completed.

4. **Filter tasks:**
   - Use the filter buttons to view all tasks, only active tasks, or only completed tasks.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.
