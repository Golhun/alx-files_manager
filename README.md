
# Backend Trimester Project

## Overview

This project encapsulates key backend concepts including authentication, NodeJS, MongoDB, Redis, pagination, and background processing. The objective is to create a simple file management platform where users can authenticate, upload, view, and manage files.

## Features

- **User Authentication**: Secure access via token-based authentication.
- **File Management**: List all files, upload new files, change file permissions, and view files.
- **Image Processing**: Generate thumbnails for image files.

## Technologies

- **Node.js**: For building the server-side application.
- **Express**: For API development.
- **MongoDB**: For database management.
- **Redis**: For managing temporary data and caching.
- **Bull**: For background job processing.
- **Mocha**: For testing.

## Getting Started

### Prerequisites

- Node.js (version 12.x.x)
- MongoDB
- Redis

### Installation

Clone the repository and install dependencies:

```bash
git clone <repository-url>
cd <project-directory>
npm install
```

### Running the Application

```bash
node app.js # or use nodemon for development
```

Ensure you are in the project's root directory when executing commands.

## Resources

- [Node.js Getting Started](https://nodejs.org/en/docs/guides/getting-started-guide/)
- [Express Documentation](https://expressjs.com/en/starter/installing.html)
- [Mocha Documentation](https://mochajs.org/)
- [Bull - Background Job Processing](https://optimalbits.github.io/bull/)

## Learning Objectives

By the end of this project, you should be able to explain:

- How to create an API with Express.
- User authentication methods.
- Data storage with MongoDB.
- Temporary data handling with Redis.
- Background job processing setup and usage.

## Requirements

- Compatible on Ubuntu 18.04 LTS.
- Code should adhere to ESLint standards.


