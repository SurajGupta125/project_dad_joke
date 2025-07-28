# project_dad_joke
This is a fun and lightweight web app built using HTML, CSS, and JavaScript. It fetches random dad jokes from the icanhazdadjoke.com API and displays them on the screen with just a click.
# 🤣 Dad Joke Generator

This is a fun and lightweight web application built with **HTML, CSS, and JavaScript**. It fetches and displays random dad jokes using the public API from [icanhazdadjoke.com](https://icanhazdadjoke.com).

---

## 🚀 Features

- 🧠 Fetches a new dad joke with each button click
- 💬 Uses the `fetch()` API with JSON headers
- 🎨 Clean, responsive design with CSS styling
- 🛑 Graceful error handling if the API fails
- ⚡ Loads a joke automatically when the page opens

---

## 🛠️ Technologies Used

- **HTML** – for page structure  
- **CSS** – for styling and layout  
- **JavaScript** – for API fetching and interactivity  
- **icanhazdadjoke API** – to get random dad jokes

---

## 💡 How It Works

1. When the page loads or the user clicks the button, a request is sent to `https://icanhazdadjoke.com/`  
2. The API returns a joke in JSON format  
3. The joke is displayed inside the webpage  
4. If there's a problem, an error message is shown instead

---

## 📋 Example Output

> "I only know 25 letters of the alphabet. I don't know y."

---

## 🧑‍💻 Author

**Suraj Gupta**  
Open-source and beginner-friendly. Feel free to use or contribute.

---

## 🧪 Fix Note

Make sure to fix the typo in the JS event:
```js
// Replace this:
window.addEventListener('DomContentLoader', dadJokes())
// With this:
window.addEventListener('DOMContentLoaded', dadJokes)
