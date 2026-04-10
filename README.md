## ⏰ Analog Clock

This is a simple and responsive analog clock created using **HTML, CSS, and JavaScript**. The clock displays the current system time and updates every second.

### ✨ Features
- Real-time clock using JavaScript `Date` object
- Smooth rotation of hour, minute, and second hands
- Clean and responsive UI design
- Lightweight and beginner-friendly project

### 🛠️ Technologies Used
- HTML
- CSS (Flexbox, Positioning, Transform)
- JavaScript (DOM manipulation, setInterval)

### ⚙️ How It Works
- The current time is fetched using the `Date` object.
- Each hand rotates based on calculated degrees:
  - Hour hand → `30 * hours + minutes / 2`
  - Minute hand → `6 * minutes`
  - Second hand → `6 * seconds`
- The clock updates every second using `setInterval`.

### 📁 How to Run
1. Clone the repository
2. Open `index.html` in your browser.......
