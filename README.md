# Social Network by Alec Worthen

## Introduction

Social Network is a robust Node.js API designed to facilitate CRUD operations on various social networking data models using a NoSQL database. This API, developed with Node.js and Mongoose, empowers users to manage friends, users, thoughts, and reactions seamlessly. By leveraging the flexibility of NoSQL databases, it offers a scalable solution for handling social networking data without the constraints of traditional relational databases.

## Table of Contents

- [Overview](#overview)
- [The Challenge](#the-challenge)
- [Usage Instructions](#usage-instructions)
- [Installation Guide](#installation-guide)
- [Technologies Used](#technologies-used)
- [Lessons Learned](#lessons-learned)
- [Future Development](#future-development)
- [Author](#author)

## Overview

### The Challenge

The primary objective was to construct a RESTful API capable of managing users, thoughts, and reactions in a social media setting using a NoSQL database. The API, crafted with Node.js and Mongoose, needed to handle vast amounts of unstructured data efficiently.

### Assigned User Story

The project aimed to fulfill the requirements of a social media startup by delivering an API that harnessed the capabilities of a NoSQL database, ensuring optimal performance with large datasets.

### Acceptance Criteria

The API needed to meet the following criteria:
- Successfully start the server and sync Mongoose models with MongoDB.
- Display formatted JSON data for user and thought endpoints via Insomnia.
- Perform CRUD operations for users and thoughts via Insomnia.
- Enable the creation and deletion of reactions to thoughts, as well as the management of a user's friend list.

## Usage Instructions

1. Clone the repository from GitHub or download the zip folder.
2. Set up a `.env` file in the project root with required variables.
3. Initiate the server and use tools like Insomnia to test API endpoints.
4. Utilize Insomnia to interact with the specified route endpoints for categories, products, and tags.

## Installation Guide

Follow these steps to set up the project:
1. Clone or download the repository.
2. Open the project in your preferred code editor.
3. Install dependencies by running `npm install` in the terminal.
4. Update `.env` file with necessary configurations.
5. Start the server using `npm start`.

## Technologies Used

- Node.js
- Mongoose
- Express
- MongoDB
- Insomnia
- Nodemon

## Lessons Learned

Throughout the project, key learnings included:
1. Construction of a RESTful API with Node.js and Mongoose.
2. Effective utilization of NoSQL databases for unstructured data management.
3. Implementation of CRUD endpoints for various data models.
4. Handling of HTTP requests and JSON data.
5. Utilization of environment variables and .env files for secure configuration.

## Future Development

Future iterations of the project may include:
1. Integration of additional features to enhance user experience.
2. Improvement of error handling mechanisms and feedback messaging.
3. Optimization of database performance for scalability.
4. Exploration of alternative NoSQL databases for suitability assessment.
5. Enhancement of API documentation to aid developers in usage.

## Author

For further inquiries, feel free to reach out to the author, Alec Worthen, via email at alecworthen@gmail.com. Follow updates on GitHub at [Alec Worthen](https://github.com/alecworthen).

© 2023 [Alec Worthen](https://github.com/alecworthen). All Rights Reserved.
