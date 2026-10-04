# 📒 Contacts App

A simple and clean **Contact Management Application** built with **React 19** and **Vite**. This app allows users to view, add, and delete contacts with ease.

---

## 🚀 Demo

> Open `index.html` after running the build, or start the dev server locally.

---

## ✨ Features

- 📋 **View Contacts** — Browse a list of contacts with profile images and tags
- ➕ **Add Contact** — Add new contacts using a simple form (name & tag)
- 🗑️ **Delete Contact** — Remove any contact from the list instantly
- 🖼️ **Profile Images** — Each contact displays an avatar photo
- ⚡ **Fast Dev Experience** — Powered by Vite for lightning-fast HMR

---

## 🛠️ Tech Stack

| Technology | Version |
|---|---|
| [React](https://react.dev/) | ^19.2.8 |
| [Vite](https://vitejs.dev/) | ^8.2.2 |
| JavaScript (ESM) | ES2020+ |
| CSS | Custom Stylesheet |

---

## 📁 Project Structure

```
contacts-app/
├── public/
│   ├── images/          # Contact profile photos
│   ├── favicon.svg
│   └── icons.svg
├── src/
│   ├── components/
│   │   ├── ContactApp.jsx       # Root component (state management)
│   │   ├── ContactInput.jsx     # Form to add new contacts
│   │   ├── ContactList.jsx      # Renders all contacts
│   │   ├── ContactItem.jsx      # Single contact card
│   │   ├── ContactItemImage.jsx # Contact avatar
│   │   ├── ContactItemBody.jsx  # Contact name & tag
│   │   └── DeleteButton.jsx     # Delete action button
│   ├── styles/
│   │   └── style.css            # Global styles
│   ├── utils/
│   │   └── data.js              # Seed / initial contact data
│   └── index.jsx                # App entry point
├── index.html
├── vite.config.js
├── eslint.config.js
└── package.json
```

---

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18+ installed

### Installation

```bash
# Clone the repository
git clone https://github.com/77ferdian/contacts-app.git

# Navigate into the project
cd contacts-app

# Install dependencies
npm install
```

### Running Locally

```bash
npm run dev
```

Then open your browser at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

Output will be in the `dist/` folder.

### Preview Production Build

```bash
npm run preview
```

---

## 📸 Screenshots

> _Coming soon — add a screenshot of the app here_

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to open an [issue](https://github.com/77ferdian/contacts-app/issues) or submit a pull request.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">
  Made with ❤️ by <a href="https://github.com/77ferdian">77ferdian</a>
</div>
