# Todo Console Application

A simple command-line to-do list application built as a learning project from Chapter 2 of the book **"Essential TypeScript"** (Manning).

## 🚀 Features

- **Task Management**: Display, add new tasks, and toggle completion status.
- **Filtering**: Filter visible tasks to show/hide already completed items.
- **Data Persistence**: Uses a local JSON database (`lowdb`) to save changes between sessions.
- **Strict Architecture**: Demonstrates Type assertions, Generics, Enums, and TypeScript class structures.

## 🛠️ Tech Stack

- **Language**: TypeScript 6+
- **Runtime**: Node.js 18+ (ESM / Node16 resolution)
- **CLI Engine**: Inquirer.js (v9)
- **Database**: Lowdb

## 💻 How to Run

1. **Install dependencies**:

   ```bash
   npm install
   ```

2. **Compile TypeScript**:

   ```bash
   npx tsc
   ```

3. **Launch the application**:
   ```bash
   node dist/index.js
   ```
