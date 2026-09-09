# Email Simulator CLI

A lightweight, object-oriented Python application that simulates messaging and inbox management between users in a terminal environment.

## Overview

This project demonstrates core Object-Oriented Programming (OOP) concepts in Python, including class composition, encapsulation, dynamic state updates, and formatted CLI output. It allows users to create profiles, dispatch emails, view unread/read statuses, and manage inbox items.

## Features

* **User Management:** Create user profiles with isolated personal inboxes.
* **Email Dispatch:** Send emails between users with automatic timestamping (`datetime`).
* **Interactive Inbox Operations:**
  * View list of incoming emails with real-time status indicators (`[Unread]` / `[Read]`).
  * Read full email content and automatically update read receipts.
  * Delete specific emails by index with safe boundary checks.
* **State Encapsulation:** Decoupled `Email`, `User`, and `Inbox` models.

## Project Structure

```text
├── email_simulator.py   # Core OOP logic and executable runner
└── README.md            # Project documentation
