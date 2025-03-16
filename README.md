# MicroBlog: Simple Blogging Platform

---

## Project Overview

**MicroBlog** is a streamlined blogging platform designed to enhance learning in web application development. This educational project is built using Express.js for server-side logic and provides fundamental blogging functionality, including user registration, authentication, posting, liking posts, and managing content.

The project is structured into multiple phases to progressively introduce key web development concepts, including persistent storage, OAuth authentication, and responsive frontend design.

---

## Learning Objectives

Through this project, I am mastering:

- **Server-side Programming**: Implementing robust backend logic using Express.js.
- **User Authentication:** Managing secure user sessions, login/logout operations, and preparing for OAuth integration.
- **Data Persistence:** Setting up database interactions to manage user-generated content.
- **Templating Engines:** Using Handlebars templates for dynamic HTML views.
- **Security Concepts:** Implementing user authentication and authorization workflows.

---

## Features

- **User Authentication:** Secure registration, login, and logout functionality.
- **Post Management:** Create, like, and delete user-generated posts.
- **Data Persistence:** Efficiently stores and retrieves user and post data.
- **OAuth Integration (Planned):** Future support for third-party OAuth login (e.g., Google, GitHub).
- **Dynamic UI:** Organized and modular views through Handlebars templating.

---

## Project Structure

```
project_root/
├── app.js                  # Main server-side application logic
├── routes/                 # Routing logic for posts and authentication
├── views/                  # Handlebars templates
├── public/                 # Static assets (CSS, images, JavaScript)
└── models/                 # Data model definitions (user, posts, etc.)
```

---

## Running the Project

### Installation
Clone and install dependencies:

```bash
git clone <your-repo-link>
cd <repo-directory>
npm install
```

### Starting the Server

```bash
npm start
```

The server will run on:
```
http://localhost:3000
```

---

## Future Enhancements

- Integrate persistent storage using databases like MongoDB.
- Implement OAuth authentication via services like Google and GitHub.
- Enhance UI/UX with responsive design and advanced frontend components.

---

## License

Licensed under the MIT License - see [LICENSE](LICENSE) for details.

---

**[Back to top](#microblog-expressjs-blogging-platform)**

