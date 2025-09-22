# Simple Web App

This is a small web application that can be served locally using Python's built-in HTTP server. It supports basic user login functionality using a JSON file to store user data.

---

## 🚀 How to Run This App

Follow these steps to run the app locally:

1. **Clone or download the project to your machine.**

2. **Open the project folder in VS Code.**

3. **Open a Terminal in VS Code:**
   - Use the menu: `Terminal` > `New Terminal`
   - Or use the shortcut: `` Ctrl + ` ``

4. **Run the following command in the terminal:**

   ```bash
   python -m http.server 8000
Open your browser and go to:

http://localhost:8000

🔐 How to Add a User (for Login)
To log in as a user, you need to manually add your credentials to the JSON file used as the user database.

Open the JSON file (e.g. users.json or whatever it's named in your project) in VS Code.

Add a user object to the file in the following format:

json
Copy code
[
{
"name": "John Doe",
"email": "john@example.com",
"password": "123456"
}
// Add more users here if needed
]
⚠️ Make sure the JSON syntax is valid (especially commas between objects if adding multiple users).

Save the file.

Go back to the browser and log in using the same email and password you just added.
