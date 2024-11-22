# User Notification Preferences API

## Description

This project is a serverless API built with **NestJS** that manages user preferences for notifications. It allows users to set preferences for different notification types (e.g., marketing, newsletter, updates) and receive notifications via different channels (email, SMS, push).

## Features

- CRUD operations for managing user preferences.
- Simulated notification sending.
- Notification log tracking (with status).
- Basic rate limiting.
- Notification statistics.

## Technologies Used

- **NestJS** (for API development)
- **MongoDB** with **Mongoose** (for data storage)
- **Jest** (for testing)
- **class-validator** (for input validation)
- **AWS Lambda** or **Vercel** (for serverless deployment)

## Setup Instructions

### Prerequisites

1. **Node.js** >= 14.x.x
2. **MongoDB** (Local or Cloud URI)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/user-notification-api.git
cd user-notification-api
