# Mini Message Board

A simple message board web application built using **Node.js, Express.js, and EJS**. Users can view messages, post new messages, and open individual messages to see their details.

## Features

- View all messages on the home page.
- Add new messages with a username and message text.
- View individual message details.
- Display the date and time when a message was added.
- Responsive and clean user interface.

## Technologies Used

- **Node.js** – JavaScript runtime
- **Express.js** – Backend web framework
- **EJS** – Templating engine for rendering dynamic HTML
- **HTML5** – Page structure
- **CSS3** – Styling and responsive design

## Getting Started

Follow these steps to run the project locally.

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your computer
- npm (included with Node.js)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/mini-message-board.git
   ```

2. Navigate to the project folder:

   ```bash
   cd mini-message-board
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the server:

   ```bash
   node app.js
   ```

5. Open your browser and visit:

   http://localhost:3000

## Project Structure

```text
mini-message-board/
├── app.js
├── routes/
│   └── indexRouter.js
├── views/
│   ├── index.ejs
│   ├── form.ejs
│   └── message.ejs
├── public/
│   └── styles.css
├── package.json
└── README.md
```

## What I Learned

- Setting up a Node.js and Express.js application.
- Creating and organizing Express routes.
- Handling GET and POST requests.
- Processing form data using Express middleware.
- Rendering dynamic pages with EJS templates.
- Passing data from routes to views.
- Using Git and GitHub to manage and share a project.

## Note

Messages are currently stored in an in-memory JavaScript array. They are not permanently saved and will reset when the server restarts.

## Future Improvements

- Add a database to store messages permanently.
- Add user authentication.
- Improve message management functionality.

---

Built as a learning project while exploring Node.js and Express.js.