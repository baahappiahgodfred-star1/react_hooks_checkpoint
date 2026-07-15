# 🎬 Movie App — React Hooks Checkpoint

This project is a small React application designed to display, add, and filter movies or TV shows.  
It was built as part of the **React Hooks Checkpoint** and demonstrates key React concepts such as **useState**, and **useEffect**

---

## 🚀 Features

### ✔ Display Movies
Each movie includes:
- **title**
- **description**
- **posterUrl** (Base64 image from uploaded file)
- **rating** (0–5)

The display is handled by the **MovieCard** component.

---

### ✔ Movie List
The **MovieList** component receives an array of movies and displays each one as a card.

---

### ✔ Add New Movies
Using the **FormMovie** component, users can:
- Add a movie through a form  
- Upload a local image (converted to Base64)  
- Save the movie to LocalStorage  
- Update the movie list instantly  

---

### ✔ Delete a Movie
Every movie card includes a delete icon.  
Deleting a movie:
- Updates the list  
- Reflects the change in LocalStorage  

---

### ✔ Filter by Title and Rating
With the **Filter** component, users can search:
- By title (text search)
- By rating (minimum rating)
a
Filtering updates the displayed movies in real-time via the `onSearch` callback.

---

### ✔ LocalStorage Persistence
All added or deleted movies remain saved locally, even after refreshing the page.

---

## 🧩 Component Structure

```
src/
│── components/
│    ├── Header.js
│    ├── Filter.js
│    ├── MovieCard.js
│    ├── MovieList.js
│    └── FormMovie.js
│
│── App.js
│── index.js
```

---

## 🛠 Technologies Used

- **React** (Hooks)
- **React Bootstrap**
- **JavaScript ES6**
- **LocalStorage**
- **FileReader API** (for Base64 conversion) for visonning the posters

---

## ▶️ Run the Project

```
npm install
npm start
```

The app will run on:  
http://localhost:3000

---

## 📌 Learning Objectives Achieved

- Managing state with **useState**
- Persisting data using **useEffect + LocalStorage**
- Component communication (props + callbacks)
- Form handling and validation
- Dynamic filtering logic
- Building a clean, modular React project structure

---


## 👨‍💻 Author

Project created by **Godfred** as part of the React Hooks Checkpoint.