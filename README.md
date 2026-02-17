# stopwatch

⏱️ Stopwatch Web Application

A simple and responsive Stopwatch Web App built using HTML, CSS, and Vanilla JavaScript. The application can start, stop, and reset time with millisecond precision using JavaScript timing functions.

📌 Features

✅ Start, Stop, and Reset controls

✅ Tracks Hours, Minutes, Seconds, Milliseconds

✅ Real-time timer updates

✅ Clean and minimal UI

✅ Responsive centered layout

✅ Button state handling (active/disabled states)

🛠️ Tech Stack

HTML5

CSS3

JavaScript (Vanilla JS)

setInterval() timing function

📂 Project Structure
stopwatch-app/
│
├── index.html     → App layout and structure
├── style.css      → UI styling
├── script.js      → Stopwatch logic
└── README.md      → Project documentation

🚀 How It Works

When Start is clicked:

A timer starts using setInterval() (10 ms interval)

Milliseconds increment continuously

Values roll over properly:

100 ms → +1 second

60 seconds → +1 minute

60 minutes → +1 hour

When Stop is clicked:

Timer pauses without resetting values

When Reset is clicked:

Timer stops

All values reset to 00

▶️ How to Run Locally

Clone the repository:

git clone https://github.com/your-username/stopwatch-app.git


Open the project folder.

Open this file in your browser:

index.html


No installation or server required ✅

🎯 Use Cases

Practice JavaScript timing functions

Beginner DOM manipulation project

UI control state management demo

Frontend mini-project submission

🚀 Future Improvements

Lap time recording

Pause/Resume toggle button

Keyboard shortcuts

Dark/light theme

Export lap times
