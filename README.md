# Secure Login Page with Express.js

This project is a simple **login authentication system** built using **Node.js, Express.js, and Body-parser**. Users must enter a predefined password to gain access to a protected page.

## Features
✅ Middleware-based password authentication  
✅ Handling POST requests with Body-parser  
✅ Serving static files with Express  
✅ Redirecting users based on authentication status  

## Technologies Used
- **Node.js**
- **Express.js**
- **Body-parser**
- **HTML, CSS, JavaScript**

## Installation & Setup
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/your-repo.git
   ```
2. Navigate to the project directory:
   ```sh
   cd your-repo
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the server:
   ```sh
   node index.js
   ```
5. Open your browser and go to:
   ```sh
   http://localhost:3000
   ```

## Project Structure
```
/your-repo
│── public/
│   ├── index.html
│   ├── thankyou.html
│   ├── styles.css
│── index.js
│── package.json
│── README.md
```

## How It Works
1. The user enters a password in the form on `index.html`.
2. The password is checked using middleware in `index.js`.
3. If correct, the user is redirected to `thankyou.html`.
4. If incorrect, they are redirected back with an error message.

## Contributing
Feel free to fork this repository and submit pull requests to enhance the project.

## License
This project is licensed under the MIT License.

---
Made with ❤️ by abhayraj

