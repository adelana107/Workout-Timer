# ⚛️ The Atomic Blog

A lightweight **React blogging app** that lets you create, search, and manage posts dynamically — with a fun dark mode toggle and a massive post archive generated using **faker.js**.

---

## 🚀 Features

- 📝 **Create new posts** instantly using a simple form.  
- 🔍 **Search posts** in real time by title or content.  
- 🗑️ **Clear all posts** with one click.  
- 🌙 **Toggle dark mode** using a fake theme switcher.  
- 🧩 **Archive section** that stores thousands of generated posts for testing.  
- ⚡ **Optimized rendering** using lazy initialization in `useState`.  
- 🔄 **Custom hook (`usePosts`)** used for managing and reading posts from context.

---

## 🧠 How It Works

1. The app generates random posts using `@faker-js/faker`.  
2. Posts can be searched, added, or cleared dynamically.  
3. The **dark mode toggle** adds/removes a `.fake-dark-mode` class on the `<html>` element.  
4. The **archive** demonstrates performance optimization using lazy initialization (`useState(() => ...)`).  
5. The `usePosts` hook provides shared post state to components like `List`.

---

## 🛠️ Technologies Used

- **React** (Hooks: `useState`, `useEffect`, custom `usePosts`)  
- **@faker-js/faker** for generating random content  
- **JavaScript (ES6+)**  
- **CSS** for layout and dark mode styling

---

## 🧩 Project Structure

src/
│
├── App.jsx
├── components/
│ ├── FormAddPost.jsx
│ ├── List.jsx
│ ├── Archive.jsx
│ ├── Header.jsx
│ ├── Footer.jsx
│ └── SearchPosts.jsx
├── hooks/
│ └── usePosts.js
├── index.jsx
└── index.css



---

## ▶️ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/the-atomic-blog.git
cd the-atomic-blog
2. Install Dependencies

npm install
3. Run the Development Server

npm run dev
Then open:


http://localhost:5173/
🖼️ Example Output

⚛️ The Atomic Blog
🚀 30 atomic posts found
[Search bar]
[Add Post form]
[List of posts...]
🌙 Toggle dark mode
💡 Future Improvements
Add categories or tags for posts.

Save posts in localStorage or a database.

Improve styling and responsive layout.

Add pagination or infinite scrolling for archives.

📄 License
This project is open-source under the MIT License.
