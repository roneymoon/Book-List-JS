# 📚 Book List App

Welcome to the **Book List App**! This is a simple yet powerful web application where users can add, remove, and store books in the browser using `localStorage`. 🚀 Built using **JavaScript**, this app provides a great way to track your reading list right within your browser! 🌐

![Book List App Preview](https://via.placeholder.com/800x400.png) <!-- Optional: Add a screenshot here -->

---

## 🌟 Features

- 📖 **Add Books**: Easily add books to your list by filling out the form with the title, author, and ISBN.
- 🗑️ **Remove Books**: Delete books from your list with a single click!
- 💾 **Persistent Storage**: Books are stored in your browser’s `localStorage`, so your list remains even after refreshing the page.
- ⚡ **Dynamic UI Updates**: The list dynamically updates when books are added or removed without refreshing the page.
- 🚨 **Validation & Alerts**: Prevent empty submissions and get visual feedback with success and error alerts.

---

## 🚀 Live Demo

Check out the live version of the app here: [Live Demo](https://example.com) <!-- Update with your live link -->

---

## 🛠️ How It Works

### 1. **Adding a Book**
- Fill in the book’s title, author, and ISBN number in the form.
- Click the `Add Book` button, and the book will appear in the list below.
- An alert will confirm the successful addition of the book.

### 2. **Removing a Book**
- Click the red ❌ next to any book to remove it from the list.
- The book will also be deleted from `localStorage`, ensuring it doesn’t reappear upon page reload.

### 3. **Data Persistence**
- All book data is stored in the browser’s `localStorage`, so even if you close the app and return later, your book list will remain intact!

---

## 🎨 UI/UX

The app is styled with a clean and minimalistic design, providing a user-friendly experience. Alerts for errors or successful operations appear at the top of the page and fade away after 1.5 seconds.

---

## 🔧 Installation

Want to run this app locally? It’s simple! Follow the steps below:

1. **Clone the repo**:
   ```bash
   git clone https://github.com/yourusername/book-list-app.git```

2. **Open the project**: Navigate to the project folder and open the `index.html` file in your browser.

---

## 📝 Code Structure

### Book Class
Handles the creation of book objects with the properties `title`, `author`, and `isbn`.

### UI Class
Handles UI tasks such as:
- Displaying books from `localStorage`
- Adding and removing books from the DOM
- Showing alerts for user feedback
- Clearing input fields after submission

### Store Class
Handles the storage of books in `localStorage`, including:
- Fetching books from storage
- Adding new books to storage
- Removing books from storage

### Event Listeners
- **DOMContentLoaded**: Loads and displays stored books when the page loads.
- **Submit Event**: Captures form input and adds a new book.
- **Click Event**: Removes a book when the delete button is clicked.

---

## 🧑‍💻 Technologies Used

- **HTML5** for the structure
- **CSS3** for styling
- **JavaScript** for interactivity
- **localStorage** for persistent data storage

---

## 📸 Screenshots

### Main Interface
![Main Interface](https://via.placeholder.com/800x400.png) <!-- Replace with actual screenshot -->

### Alerts and Form
![Alerts](https://via.placeholder.com/800x400.png) <!-- Replace with actual screenshot -->

---

## 🤝 Contributing

Want to contribute? Awesome! Follow the steps below:

1. Fork the project.
2. Create your feature branch: `git checkout -b feature/amazing-feature`.
3. Commit your changes: `git commit -m 'Add amazing feature'`.
4. Push to the branch: `git push origin feature/amazing-feature`.
5. Open a pull request.

---

## 🧾 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

Feel free to reach out for suggestions or collaborations:

- **GitHub**: [yourusername](https://github.com/yourusername)
- **Email**: your.email@example.com

---

**Enjoy using the Book List App! Happy reading! 📚✨**
