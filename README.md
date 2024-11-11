# Blog_Sphere

Welcome to the **Blog_Sphere** repository! This project is a responsive and visually engaging platform designed for seamless integration across different blog categories, including **Food**, **Tech**, and **News**. Built with a modular frontend and backend architecture, this site enables users to navigate through various content categories with ease.

---
## Demo

Check out the live demo of the project [here](https://cheery-bienenstitch-ef9676.netlify.app/).
---

## Table of Contents
1. [Features](#features)
2. [Tech Stack](#tech-stack)
3. [Installation](#installation)
4. [Backend Setup](#backend-setup)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)

---

## Features
- **Dynamic Category Pages**: Toggle between blog categories with smooth transitions.
- **Responsive Design**: Optimized for both desktop and mobile viewing.
- **Modular Code Structure**: Easy to extend and customize each category.
- **API Integration**: Ready for backend integration to fetch and manage blog data dynamically.

---

## Tech Stack

### Frontend
- **HTML5**
- **CSS3**
- **JavaScript** (Vanilla/ES6)
- **Bootstrap** (for responsive layout)

### Backend
- **Node.js** with **Express.js** (for API and server)
- **MongoDB** (for database)

---

## Installation

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or higher)
- [MongoDB](https://www.mongodb.com/) (either locally or using a cloud provider like MongoDB Atlas)
- [Git](https://git-scm.com/)

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/username/Blog_Sphere.git
   cd Blog_Sphere
   ```
### Frontend Setup
- All frontend files are in the `public` directory.
- Open `index.html` in the browser to view the static frontend without backend integration.

### Backend Setup (For dynamic functionality)
1. Navigate to the `server` directory.
2. Run the following commands to set up the backend:
   ```bash
   npm install
   ```
## Backend Setup

### Database Configuration
1. Create a `.env` file in the `server` directory.
2. Add the MongoDB URI and other environment variables:
   ```plaintext
   MONGODB_URI=mongodb://localhost:27017/blog_sphere_db
   PORT=5000
   ```

### Run the Server
1. Start the server with the following command:
   ```bash
   node server.js
   ```
-The server should start on http://localhost:5000.

### Connecting Frontend with Backend
- Update any API endpoint references in the frontend to connect with the backend server.

### Usage
Once the backend server is running, you can access the dynamic features of the site by navigating to `http://localhost:5000` in your browser.

### Contributing
Contributions are welcome! Please fork this repository, create a feature branch, and submit a pull request.

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



   
