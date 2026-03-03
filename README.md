# TalkTheTalk (TTT)

TalkTheTalk is a React-based web application that combines a stopwatch with speech synthesis functionality.  
The application allows users to define custom time triggers that automatically play predefined spoken messages.

## 🚀 Features

- Stopwatch functionality
- Custom time-based speech triggers
- Dynamic timer configuration
- Add and edit multiple speech timers
- Automatic reset after the final timer
- Real-time UI updates

## 🛠 Technologies Used

- React
- React Hooks (useState, useEffect, useCallback)
- react-timer-hook
- react-speech-kit
- CSS

## 🎯 How It Works

1. The stopwatch starts counting seconds.
2. When the current time matches a configured timer,
   the application triggers a speech message.
3. Users can:
   - Add new timers
   - Edit existing timers
   - Define custom text for each time trigger
4. Once the last timer is reached, the stopwatch resets automatically.

## ▶ How to Run Locally

1. Clone the repository  
2. Run `npm install`
3. Run `npm start`
4. Open `http://localhost:3000`

## 🌍 Live Demo

(Add GitHub Pages or deployment link here)

## 📚 What I Learned

- Managing state with React Hooks
- Handling side effects with useEffect
- Working with browser Speech Synthesis API
- Managing time-based triggers
- Structuring reusable components
- Building dynamic user-driven UI logic

## 💡 Possible Improvements

- Persist timers in local storage
- Add pause functionality
- Improve UI styling and responsiveness
- Add validation for duplicate time entries

## 📸 Preview
<img width="1917" height="917" alt="TTT" src="https://github.com/user-attachments/assets/24002693-7f29-40b9-a7d8-cd23366d4b0a" />
