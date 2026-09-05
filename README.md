# Ordinox Desk

**Desktop client and business management application for Windows.**

Ordinox Desk is a desktop application designed to help small businesses manage clients, appointments, services, revenue, reminders and everyday business workflows from a single interface.

The project started as an initial concept and was developed iteratively into a functional Windows desktop application, with a strong focus on usability, structured data management, reliability and practical day-to-day operation.

---

## Tech Stack

- **Tauri v2** — Windows desktop application framework
- **Rust** — native Tauri application layer and packaging
- **HTML**
- **CSS**
- **JavaScript**
- **Local browser/WebView storage** for application data
- **Windows installer packaging**

The application combines a web-based user interface with Tauri's native desktop environment, allowing it to run as a standalone Windows application rather than only inside a browser.

---

## Application Preview

### Calendar & Appointment Management

![Ordinox Desk Calendar](assets/screenshots/calendar.png)

The application includes an appointment management system with:

- New appointment creation
- Date and time management
- Client information
- Service selection
- Price tracking
- Notes
- Appointment search
- Upcoming appointments
- Calendar-based navigation
- Appointment completion tracking

---

### Client Management

![Ordinox Desk Clients](assets/screenshots/clients.png)

Ordinox Desk includes a structured client management system designed for quick access to customer information and related business activity.

Features include:

- New client creation
- Client editing
- Search and filtering
- Organized client list
- Client history
- Related appointments and services
- Quick access to client actions and records

---

### Client Details

![Ordinox Desk Client Details](assets/screenshots/client-details.png)

Each client can have a dedicated record containing relevant information and business history.

The goal is to keep useful client information accessible from one place instead of relying on multiple applications, documents or spreadsheets.

---

### Revenue Management

![Ordinox Desk Revenue](assets/screenshots/revenue.png)

The application includes tools for organizing and reviewing revenue-related information.

This allows the user to obtain a practical overview of financial data associated with appointments, services and business activity.

---

### Reminders

![Ordinox Desk Reminders](assets/screenshots/reminders.png)

A dedicated reminder system helps users keep track of important tasks and obligations directly inside the application.

This keeps business-related reminders together with the rest of the client's workflow instead of requiring a separate application.

---

### Services

Ordinox Desk includes service management functionality, allowing commonly provided services to be organized and reused throughout the application.

This helps maintain consistent data while reducing repetitive manual entry.

---

### Backup & Import

![Ordinox Desk Backup and Import](assets/screenshots/backup-import.png)

Data protection and portability were important parts of the project.

The application includes functionality for:

- Data backup
- Data export
- Data import
- Recovery of stored information

The purpose is to ensure that business data is not dependent on a single application installation.

---

## Windows Desktop Application

Ordinox Desk is packaged as a standalone Windows desktop application using **Tauri**.

The project includes configuration for:

- Native Windows application execution
- Application identity and branding
- Application icons
- Release builds
- Windows packaging
- Installer generation

This allows the application to be installed and used like a normal Windows program rather than requiring the user to manually open source files or run a development environment.

---

## Development Approach

Ordinox Desk was developed incrementally rather than through large one-time rewrites.

The development process includes:

- Feature planning
- Implementation
- Behavior verification
- Debugging
- Problem identification
- UI/UX refinement
- Regression checking after changes
- Data safety considerations
- Windows packaging and installer testing

Features and fixes are implemented in controlled steps so that existing functionality can be checked after each change.

---

## AI-Assisted Development

AI-assisted software development is an important part of my workflow, particularly using **OpenAI Codex**.

AI tools are used for:

- Code analysis
- Feature implementation
- Debugging
- Identifying potential issues
- Refactoring and code refinement
- Investigating alternative implementations
- Reviewing the possible impact of changes
- Assisting with testing and validation
- Analyzing existing application architecture

AI-generated changes are not applied blindly.

Changes are reviewed and tested incrementally, with particular attention to preserving existing functionality and avoiding unrelated modifications.

This workflow combines AI-assisted implementation with human review, testing and product decisions.

---

## What I Learned From This Project

Developing Ordinox Desk has given me practical experience in:

- Building a complete desktop application from an initial idea
- Desktop application architecture
- Client and business data management
- Application state and local data persistence
- UI/UX design and refinement
- Feature implementation
- Debugging and troubleshooting
- Regression testing
- Data backup and recovery workflows
- Windows application configuration
- Tauri and Rust-based desktop packaging
- Windows installer preparation
- Iterative product development
- AI-assisted software development
- Using Codex as part of a real development workflow

---

## Development Philosophy

One of the main goals of the project is to improve functionality without introducing unnecessary regressions.

For significant changes, I follow a workflow based on:

1. Understanding the existing behavior
2. Identifying the smallest appropriate change
3. Implementing the change
4. Reviewing the affected files
5. Building or testing the application
6. Verifying that existing functionality still behaves correctly
7. Avoiding unrelated changes

This approach has become particularly important when working with AI-assisted coding tools.

---

## Test Data & Privacy

All names, telephone numbers, appointments and other personal information visible in the screenshots in this repository are **fictional test data**.

They do not represent real clients or individuals.

No production client data is included in this portfolio repository.

---

## Source Code

The production source code of Ordinox Desk is currently maintained privately.

This repository is intended as a **project showcase and portfolio presentation**, containing documentation and visual material demonstrating the application's functionality and development process.

Selected source code or additional technical material may be provided when appropriate.

---

## Project Status

**Active personal software project.**

Ordinox Desk is a functional Windows desktop application and continues to evolve through additional features, bug fixes and usability improvements.
