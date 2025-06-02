# Smart Expense Tracker

A cross-platform (Android, iOS, and Web) Flutter app for tracking your expenses smartly.

## Features

- Add, view, and delete expenses
- Categorize expenses
- View analytics of total spending
- Persistent storage using Hive (works on all platforms)
- Responsive design for all platforms

## Getting Started

1. Clone the repo:
   ```
   git clone https://github.com/dmanivannancse/smart_expense_tracker.git
   cd smart_expense_tracker
   ```

2. Get dependencies:
   ```
   flutter pub get
   ```

3. Generate Hive adapters:
   ```
   flutter pub run build_runner build
   ```

4. Run on your chosen platform:
   ```
   flutter run -d chrome    # For web
   flutter run -d android   # For Android
   flutter run -d ios       # For iOS
   ```