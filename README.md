# Ordinox Desk

**Local-first Windows desktop application for client and small-business management.**

[English](README.md) · [Ελληνικά](README_GR.md)

---

## Overview

Ordinox Desk is a Windows desktop application designed to help small businesses manage clients, appointments, services, revenue, reminders and everyday business workflows from a single interface.

The goal is to keep useful client and business information organized in one place, without depending on multiple spreadsheets, documents or separate tools.

The application follows a **local-first approach**, with normal business data managed locally on the user's Windows device.

It is designed for **Windows PCs and Windows tablets**, with **English and Greek interface support**.

> **Portfolio showcase:** This public repository presents the application and its interface. The production source code is maintained privately and is not published here.

> **Demo data:** All names, phone numbers, appointments, prices and other personal or business information visible in the screenshots are fictitious demonstration data.

---

## Calendar & Appointment Management

![Ordinox Desk Calendar](assets/screenshots/calendar.png)

The application includes a practical appointment-management workflow with:

- New appointment creation
- Date and time management
- Client information
- Service selection
- Price tracking
- Notes
- Appointment search
- Upcoming appointments
- Calendar-based navigation
- Appointment status management

The goal is to keep daily scheduling connected with the rest of the client and business workflow.

---

## Client Management

![Ordinox Desk Clients](assets/screenshots/clients.png)

Ordinox Desk includes a structured client-management system designed for quick access to customer information and related activity.

Features include:

- New client creation
- Client editing
- Client search
- Organized client list
- Client-related information
- Access to previous activity
- Quick access to relevant actions and records

---

## Client Details

![Ordinox Desk Client Details](assets/screenshots/client-details.png)

Each client can have a dedicated record containing relevant information and business history.

The purpose is to keep useful client information accessible from one place instead of relying on multiple applications, documents or spreadsheets.

---

## Revenue Management

![Ordinox Desk Revenue](assets/screenshots/revenue.png)

The application includes tools for organizing and reviewing revenue-related information.

This provides a practical overview of financial information associated with appointments, services and business activity.

---

## Reminders

![Ordinox Desk Reminders](assets/screenshots/reminders.png)

A dedicated reminder system helps users keep track of important tasks and obligations inside the same application.

This allows business-related reminders to remain connected to the rest of the workflow instead of requiring a separate tool.

---

## Services

Ordinox Desk includes service-management functionality, allowing commonly provided services to be organized and reused throughout the application.

This helps:

- Reduce repetitive data entry
- Keep service information consistent
- Reuse common services
- Connect appointments with the services provided
- Keep business activity organized

---

## Backup & Import

![Ordinox Desk Backup and Import](assets/screenshots/backup-import.png)

Data portability and recovery are important parts of the application.

Available functionality includes:

- Local data backup
- JSON data export
- Data import
- Validation and normalization of imported data
- Recovery of stored information
- Protection against invalid or unexpected imported data

This allows users to keep copies of their data independently from the application installation.

---

## Local-First Architecture

Ordinox Desk is designed to operate locally on the user's Windows device.

For normal operation:

- No remote backend is required
- No external database server is required
- No cloud account is required
- Application data is stored locally
- Backup files can be exported by the user
- Existing data can be restored through the import workflow
- Continuous internet connectivity is not required

This makes the application suitable for businesses that prefer a straightforward standalone desktop solution.

---

## Windows PC & Tablet

Ordinox Desk runs as a standalone Windows desktop application using **Tauri 2**.

It is designed for use on:

- Windows desktop computers
- Windows laptops
- Windows tablets

The interface is intended to remain practical across different Windows screen sizes.

The application can be provided with **English and Greek interface support**.

---

## Product Philosophy

Ordinox Desk is designed around a simple idea:

**keep client information, appointments, services, revenue, reminders and everyday business activity together in one practical application.**

The goal is not to create unnecessary complexity, but to provide useful tools for day-to-day business organization.

Depending on the business and user needs, additional optional features or tailored functionality may be added over time.

---

## Future Commercial Model

For future commercial releases, the intended model is straightforward:

- One-time purchase
- Local installation
- No mandatory ongoing subscription to continue using the purchased version
- Local management of normal application data

Additional optional functionality or customized versions may be offered depending on the needs of the user or business.

---

## Technology

Ordinox Desk is built using technologies including:

- **Tauri 2**
- **Vanilla JavaScript**
- **HTML5**
- **CSS3**
- **WebView local storage**
- **JSON**
- **Windows desktop packaging**

The user interface and main business logic are implemented primarily with HTML, CSS and JavaScript, while Tauri provides the native Windows runtime and packaging environment.

---

## Development Approach

Ordinox Desk has been developed incrementally rather than through large one-time rewrites.

The development process includes:

1. Understanding the existing behavior
2. Planning the required feature or fix
3. Implementing focused changes
4. Reviewing affected code
5. Running and testing the application
6. Checking existing functionality for regressions
7. Refining the interface where necessary
8. Avoiding unrelated modifications

This approach helps keep the application understandable and stable while it evolves.

---

## AI-Assisted Development

AI-assisted software development is part of my workflow, including the use of **OpenAI Codex**.

AI tools are used for tasks such as:

- Existing code analysis
- Feature implementation
- Debugging
- Identifying potential issues
- Code refinement
- Exploring alternative implementations
- Reviewing possible side effects
- Testing and validation assistance

AI-generated changes are not applied blindly.

Changes are reviewed and tested incrementally, combined with manual verification, debugging and product decisions.

---

## Data Handling & Reliability

As the application evolved, particular attention was given to handling local business data safely and predictably.

The project includes logic for areas such as:

- Input validation
- Data normalization
- Backup and import workflows
- Recovery from malformed stored data
- Safer handling of user-controlled values
- CSV-compatible data handling
- Rollback behavior where appropriate

---

## Test Data & Privacy

All names, telephone numbers, appointments, prices and other personal or business information visible in the screenshots are **fictional demonstration data**.

They do not represent real clients or individuals.

No real client data is included in this portfolio repository.

---

## Source Code

The full production source code of Ordinox Desk is maintained privately.

This repository is intended as a **product showcase and portfolio presentation**, containing documentation and visual material demonstrating the application's functionality.

The complete production source code is not included in this public repository.

---

## Project Status

**Functional Windows desktop software project.**

Ordinox Desk is a working application focused on practical client and small-business management.

The product can continue to evolve with additional optional features and configurations for different professional or business needs.

---

## Author

Designed and developed by **Menelaos Tzatzanis**.

Part of the **ORDINOX** desktop software project family.

© 2026 Menelaos Tzatzanis. All rights reserved.
