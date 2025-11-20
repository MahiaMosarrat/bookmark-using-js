# 📚 Bookmark Manager Using JavaScript

A practical project demonstrating how to create, save, and manage multiple bookmarks using **vanilla JavaScript**, **HTML**, and **CSS**.  
This project covers essential JavaScript concepts including **DOM Manipulation**, **arrays & objects**, **array forEach**, **JSON parse/stringify**, **variables and scope**, **callback functions**, and **arrow functions**.

---

## 🔗 Live Demo  
👉 (https://multiple-bookmark-app.netlify.app/)

---

## 📸 Screenshot

| Bookmark Manager Interface |
|----------------------------|
|  <img width="1466" height="871" alt="image" src="https://github.com/user-attachments/assets/e856b7c9-a863-4e6c-af67-d21bbb8baaae" />
 | <img width="1901" height="873" alt="image" src="https://github.com/user-attachments/assets/c2d34c1b-c70d-4f0f-8101-b534d09a81a8" />


---

## 🎯 Project Overview

This project allows users to:

- Add multiple bookmarks for different websites  
- View saved bookmarks dynamically  
- Keep bookmarks saved using **localStorage** so they persist across page reloads  
- Delete unwanted bookmarks from the list  

The app uses JavaScript to manage bookmarks efficiently and interactively.

---

## 🚀 Features

- 🖱️ **Add bookmarks dynamically**  
- 💾 **Save bookmarks in browser storage (localStorage)**  
- 🗑️ **Delete bookmarks on demand**  
- 🎨 Responsive and clean UI  

---

## 🧩 How It Works

### 📂 Project Structure

- **index.html** — Contains the markup for the bookmark form and list display.  
- **style.css** — Styles the form, buttons, and bookmark list.  
- **script.js** — Handles all JavaScript logic including:  
  - DOM selection and manipulation  
  - Managing bookmarks as objects inside an array  
  - Using `localStorage` to save and retrieve bookmarks as JSON strings  
  - Adding and removing bookmarks dynamically  

### 🛠️ Bookmark Management Flow

1. User fills out the bookmark form (site name and URL)  
2. JavaScript validates the inputs  
3. If valid, the bookmark is added to an array and saved to `localStorage`  
4. The bookmark list is dynamically rendered on the page  
5. User can delete any bookmark, which updates the array and `localStorage` accordingly  

---

## 🎓 JavaScript Concepts Covered

- 📌 **DOM Manipulation** — Selecting and updating HTML elements dynamically  
- 📌 **Arrays & Objects** — Storing bookmarks as objects inside an array  
- 📌 **Array forEach** — Looping through bookmarks to render them  
- 📌 **JSON parse/stringify** — Saving and retrieving complex data structures in localStorage  
- 📌 **Variables and Scope** — Using `let` and `const` appropriately  
- 📌 **Callback Functions** — Handling events and updates  
- 📌 **Arrow Functions** — Cleaner, modern function syntax  

---

## ▶️ How to Run Locally

1. **Clone the repository**  
   ```sh
   git clone https://github.com/MahiaMosarrat/bookmark-using-js.git
2. Open the project folder
3. Open index.html in any modern browser
4. Use the form to add, view, and delete bookmarks
