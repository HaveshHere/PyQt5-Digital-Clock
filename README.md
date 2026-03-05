# 🕒 PyQt5-Digital-Clock

A simple desktop digital clock application built using Python and PyQt5.

## 🛠️ Features

- Real-Time Clock: Displays the current system time and updates automatically every second.
  
- Digital Display: Uses a custom digital font to mimic a classic LED clock style.
  
- Clean Interface: Minimal black background with bright digital text for clear visibility.
  
- Automatic Updates: Uses QTimer to refresh the time display continuously.

## ⚙️ How It Works

The application retrieves the current system time using QTime.currentTime() and updates the display every second through a QTimer. The time is formatted in HH:MM:SS AM/PM format and rendered using a QLabel in the PyQt5 graphical interface.

## 💭 How Can it be Improved?

- Add 12-hour / 24-hour time format switching.
  
- Display the current date.
  
- Add alarm functionality.
  
- Allow custom themes or colors.
  
- Create a fullscreen clock mode.
