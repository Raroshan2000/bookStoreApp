# 📚 BookStore App

A full-stack **Book Store Web Application** built with the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). Browse, add, edit, and delete books through a clean and responsive UI.

---

## 🚀 Features

- 📖 View all books in a list/card view
- ➕ Add new books to the store
- ✏️ Edit existing book details
- 🗑️ Delete books from the store
- 🔗 RESTful API backend
- 🌐 CORS-enabled for frontend-backend communication

---

## 🛠️ Tech Stack

| Layer      | Technology                          |
|------------|--------------------------------------|
| Frontend   | React.js, React Router, Axios        |
| Backend    | Node.js, Express.js                  |
| Database   | MongoDB, Mongoose                    |
| Styling    | CSS / Tailwind CSS                   |

---

## 📁 Project Structure

```
bookStoreApp/
├── Backend/
│   ├── models/         # Mongoose schemas
│   ├── routes/         # Express API routes
│   ├── index.js        # Entry point
│   └── .env            # Environment variables
│
└── Frontend/
    ├── src/
    │   ├── components/ # Reusable UI components
    │   ├── pages/      # Page-level components
    │   └── main.jsx    # React entry point
    └── index.html
```

---

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14+)
- [MongoDB](https://www.mongodb.com/) (local or Atlas)
- npm or yarn

---

### 🔧 Backend Setup

```bash
cd Backend
npm install
```

Create a `.env` file in the `Backend` folder:

```env
PORT=5555
MONGODB_URL=your_mongodb_connection_string
```

Start the backend server:

```bash
npm run dev
```

The backend runs on `http://localhost:5555`

---

### 💻 Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

The frontend runs on `http://localhost:5173`

---

## 🔌 API Endpoints

| Method | Endpoint         | Description          |
|--------|------------------|----------------------|
| GET    | `/books`         | Get all books        |
| GET    | `/books/:id`     | Get a single book    |
| POST   | `/books`         | Add a new book       |
| PUT    | `/books/:id`     | Update a book        |
| DELETE | `/books/:id`     | Delete a book        |

---

## 🖥️ Screenshots

> Add your screenshots here after running the app locally.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [MERN Stack](https://www.mongodb.com/mern-stack)
- [React Documentation](https://react.dev/)
- [Express.js Documentation](https://expressjs.com/)
