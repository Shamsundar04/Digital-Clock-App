# Digital Clock & Calendar App

A simple Digital Clock and Calendar Web App built using HTML, CSS, and JavaScript.  
This app displays the **current time** (hours, minutes, seconds) in **12-hour format with AM/PM**, along with the **current date, day, month, and year** — all updated dynamically in real-time.

---

# Features

- Live Digital Clock** — Updates every second using JavaScript’s `setInterval()`.  
- 12-Hour Format with AM/PM** — Automatically converts 24-hour time into 12-hour format.  
- Calendar Display** — Shows current day name, month name, date number, and year.  
- Automatic Time & Date Refresh** — No page reload required.  
- Clean & Readable Code** — Modular functions for each operation (time format, leading zeros, AM/PM, etc.).

---

#   Functions Overview

| Function Name | Description |
|----------------|-------------|
| `clock()` | Fetches and updates the current time (hours, minutes, seconds). |
| `setTimePeriod(time)` | Determines and returns “AM” or “PM” based on the hour. |
| `period(time)` | Converts 24-hour format into 12-hour format. |
| `addZero(time)` | Adds a leading zero to single-digit numbers. |
| `setCalendarValue()` | Displays the current day, month, date, and year. |

---

# Technologies Used

- HTML5 – For structure  
- CSS3 – For styling (customizable)  
- JavaScript (Vanilla JS) – For real-time logic and DOM manipulation  

---

#Project Structure

