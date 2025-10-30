# 🏋️‍♂️ Workout Timer

A simple and interactive **React app** that helps you track workouts and exercises dynamically based on the time of day. The app updates every second, toggles sound effects, and provides different workout options depending on whether it’s **AM or PM**.

---

## 🚀 Features

- ⏱️ **Live Time Update** — Automatically updates every second using `setInterval`.
- 🌗 **Dynamic Workouts** — Number of exercises changes based on whether it’s AM or PM.
- 🔊 **Sound Toggle** — Easily enable or disable workout sounds with the `ToggleSounds` component.
- 🧮 **Custom Calculator Component** — Calculates workout sessions based on user settings.
- ⚡ **Optimized with useMemo** — Ensures workouts are only recalculated when needed.
- 💅 **Clean, Modular Components** — Easy to extend and maintain.

---

## 🧩 Components

### `App.jsx`

The main component that:

- Keeps track of the current time.
- Determines the part of the day (AM or PM).
- Updates workout plans accordingly.
- Passes props to `ToggleSounds` and `Calculator`.

### `ToggleSounds.jsx`

Handles enabling and disabling sound effects for workouts.

### `Calculator.jsx`

Handles workout calculation logic — uses the workout data provided by the `App` component.

---

## 🛠️ Technologies Used

- **React** (with Hooks: `useState`, `useEffect`, `useMemo`)
- **JavaScript (ES6+)**
- **Intl.DateTimeFormat API** for formatting the current time

---

## 🧠 How It Works

1. The app formats the current date and time using the `formatTime()` function.
2. Every second, the time updates via `setInterval`.
3. The app extracts the last two characters from the time string to check if it’s **AM** or **PM**.
4. Using `useMemo`, it adjusts workout routines depending on the time of day.
5. `ToggleSounds` allows you to control sound feedback.
6. The `Calculator` component uses the workout data to display session details.

---

## 🏗️ Project Structure

src/
│
├── App.jsx
├── Calculator.jsx
├── ToggleSounds.jsx
├── index.jsx
└── index.css

yaml
Copy code


---

## ▶️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/workout-timer.git
cd workout-timer
2. Install Dependencies
<<<<<<< HEAD


=======
bash
Copy code
>>>>>>> 6d92238 (Save local changes before pull)
npm install
3. Run the Development Server
bash
Copy code
npm run dev
Then open:

<<<<<<< HEAD


http://localhost:5173/
🧩 Example Output
csharp


=======
arduino
Copy code
http://localhost:5173/
🧩 Example Output
csharp
Copy code
>>>>>>> 6d92238 (Save local changes before pull)
Workout timer
For your workout on Oct 29, 25, 10:45:30 AM
[Toggle Sounds Button]
[Workout Calculator Interface]
💡 Future Improvements
Add custom workout creation.

Add progress tracking and timer countdowns.

Include sound effects and animations.

Save sound preferences in local storage.

📄 License
This project is open-source under the MIT License.
```
