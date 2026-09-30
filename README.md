#  Study Flow — Flash Card Quiz

A simple **Flutter Flash Card app** for creating, reviewing, and memorizing questions and answers.

## ✨ Features

* 🃏 Create, edit, and delete flash cards
* 🔄 Flip cards to reveal answers
* 👆 Swipe between cards
* ⬅️➡️ Next / Previous navigation
* 💾 Save cards locally using Hive
* 🎨 Clean and responsive UI
* 🗂️ Empty state when no cards are available
* ⚡ Cubit for state management

## 🛠️ Tech Stack

* **Flutter & Dart**
* **Flutter Bloc / Cubit**
* **Hive**
* **flip_card_plus**
* **Google Fonts**
* **Equatable**

## 📂 Project Structure

```text
lib/
├── core/
│   ├── model/
│   ├── state_mangment/
│   └── themeing/
│
├── feature/
│   ├── ui/
│   │   ├── home_screen/
│   │   └── add_screen/
│   └── widget/
│
├── main.dart
└── flash_card.dart
```

## 🚀 Run the Project

```bash
git clone https://github.com/your-username/flash_card_quiz.git
cd flash_card_quiz
flutter pub get
dart run build_runner build
flutter run
```

## 📸 About the App

Study Flow lets you quickly create your own flash cards and review them through a simple interactive interface.

---

### 📄 License

This project is licensed under the MIT License.
