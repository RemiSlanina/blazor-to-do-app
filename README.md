# Blazor To-Do App

A small project I built to **explore Blazor, C#, and .NET** and learn. This app helped me experiment with state management, event handling, and local storage persistence.

---

## Features

- Add tasks – Type and add new tasks to your list.
- Delete tasks – Remove tasks you no longer need.
- Toggle completion – Mark tasks as completed or undo them.
- Persistent storage – Tasks are saved to `localStorage` and persist across browser sessions.

---

## What I Explored

This project was a learning exercise for me. I wanted to try out:

- **LocalStorage interop** (saving/loading tasks).
- **CRUD operations** (add, delete, mark as complete).
- **Data binding** (two-way binding for task input).
- **Conditional rendering** (e.g., strikethrough for completed tasks).

---

## Running Locally

1. **Prerequisites**:
   - [.NET SDK](https://dotnet.microsoft.com/download) (version 8.0 or later).

2. **Run the app**:
   ```
   dotnet run
   ```

Open the URL displayed in the terminal (usually http://localhost:5192 or similar).

## License

- The code in this repository is licensed under the [MIT License](./LICENSE).
