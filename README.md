# Todo Application (In Development)

A **Todo Application** built with **React Native** and **Expo**, designed to provide a seamless task management experience. This project is currently **under active development**.

---

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Architecture](#architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Project Status](#project-status)
- [Contributing](#contributing)
- [License](#license)
- [Repository](#repository)

---

## Features
- Create, read, update, and delete tasks (CRUD operations)
- Tab-based navigation for different task categories
- Scrollable task lists for better UX
- Responsive UI optimized for mobile devices
- Backend integration using **Convex** for real-time updates and serverless functions

---

## Tech Stack
- **Frontend:** React Native with Expo
- **Navigation:** React Navigation (Stack & Tab navigation)
- **Backend:** Convex (Serverless backend functions and database)
- **UI Components:** FlatList, ScrollView

---

## Architecture
The app follows a modular architecture with clear separation between layers:

### 1. UI Layer
- Implements screens, components, and navigation.
- Uses `FlatList` and `ScrollView` for efficient rendering of task lists.

### 2. State & Data Layer
- Manages local state and handles API calls to the backend.
- Real-time data sync using **Convex** client.

### 3. Backend Layer
- Built with **Convex functions** to handle business logic (task creation, updates, deletion, etc.).
- Real-time database for task updates across devices.



## Screenshots

<img src="https://github.com/user-attachments/assets/d1d0f42b-724d-4ab4-9aa9-0d8003f0b95f" alt="Screenshot 1" width="300" />
<img src="https://github.com/user-attachments/assets/0843f29d-6ab7-43ca-a839-c4d64831aaca" alt="Screenshot 2" width="300" />
<img src="https://github.com/user-attachments/assets/c7cc4732-9170-471f-9ea2-526abef3e187" alt="Screenshot 3" width="300" />
<img src="https://github.com/user-attachments/assets/bb78663b-edb3-4edd-b189-393fbca72f12" alt="Screenshot 4" width="300" />
<img src="https://github.com/user-attachments/assets/1eeb1604-1332-465f-aa0a-fcece7911433" alt="Screenshot 5" width="300" />






---

## Installation
Clone the repository and install dependencies:

```bash
# Using npm
git clone https://github.com/techbysundaram/todo.git
cd todo
npm install

# Or using yarn
git clone https://github.com/techbysundaram/todo.git
cd todo
yarn install
```


## Usage

### Start the application using Expo:

```bash
npx expo start
```

- The app will run on a simulator or a physical device via the Expo Go app.

- Navigate through tabs to manage your tasks.

## Project Status

- Active development in progress.

- Core features such as CRUD operations and tab navigation are implemented.

- Upcoming features:

  - Task prioritization and categorization

  - Notifications and reminders

  - Offline-first support

## Contributing

Contributions are welcome! Follow these steps:

- 1. Fork the repository

- 2. Create a new branch:

```bash
git checkout -b feature-name
```

- 3. Make your changes and commit:

```bash
git commit -m 'Add feature'
```

- 4. Push to the branch:

```bash
git push origin feature-name
```

- 5. Create a Pull Request

## License

This project is licensed under the MIT License. See the LICENSE file for details.
