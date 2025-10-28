# Book-Finder

# 📚 Book Finder

Book Finder is a simple and elegant web application built using **React** and **Tailwind CSS**.  
It allows users to search for books by title using the **Open Library API** — a free and public API that requires no authentication.

---

## 🚀 Features

- 🔍 **Book Search:** Search for books by title (e.g., “Harry Potter”, “1984”, “The Great Gatsby”).
- 🧾 **Detailed Results:** Displays book details like author, publication year, edition count, and publisher.
- 🖼️ **Book Covers:** Dynamically loads book cover images from the Open Library database.
- ⚡ **Responsive Design:** Fully responsive interface styled with Tailwind CSS.
- 💬 **Error Handling:** Handles network errors, invalid inputs, and empty search results gracefully.
- 🎨 **Smooth UI Enhancements:** Includes fade-in transitions and loading animations for a modern feel.

---

## 🧩 Technology Stack

| Category | Technology Used |
|-----------|-----------------|
| **Framework** | [React](https://react.dev/) (via CDN) |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) |
| **Data Fetching** | [Open Library API](https://openlibrary.org/developers/api) |
| **State Management** | React Hooks (`useState`, `useEffect`, `useRef`) |
| **Build Tool** | Babel (via CDN for JSX transformation) |

---

## ⚙️ How It Works
https://openlibrary.org/search.json?title=<book_title>&limit=20

3. The API returns a list of matching books with details like title, author, and publication year.
4. Results are displayed in a responsive grid layout with book covers and a link to the book’s Open Library page.

---

## 🛠️ Setup Instructions

You can run this project directly in the browser — no build process required.
rs a book title in the search bar.  
2. The app sends a request to the **Open Library API**:  
