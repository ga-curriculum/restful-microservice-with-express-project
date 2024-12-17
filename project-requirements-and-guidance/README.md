<h1>
  <span class="headline">RESTful Microservice with Express Project</span>
  <span class="subhead">Project Requirements and Guidance</span>
</h1>

## Overview

**Objective**:

In this project, you'll build a RESTful API Microservice using Express.js that interacts with AWS DynamoDB to manage a resource. You'll implement basic CRUD operations and ensure proper error handling and data validation. The application will be containerized with Docker for easy deployment. Testing will be conducted using Postman to verify functionality. This project will help you gain hands-on experience with Express, DynamoDB, and Docker, while practicing best practices for backend development.

**Scope and Complexity**:

For your project, you will be building an API using **JavaScript**, **Docker**, and **Terraform**.

We previously made an "Accounts" API in class, but now it's your time to build one on your own. Think of a service that you would like to build— as a starting point, we suggest an API that would make your company a "greener" organization.

**Previous ideas have included:**

- Ride Sharing API
- Office Equipment Swap API
- Carbon Offset API

However, you're free to build whatever API you like, so don't feel you have to stick to the "green theme." Follow the steps carefully, and you'll have a working, containerized API.

The project is estimated to take around **15 hours** to complete.

**_You will work individually on this project_**.

> ❗️ As a reminder, General Assembly has a zero-plagiarism policy. **_Your project's code must be substantially yours_**. Do not copy code from similar projects or other sources. However, using code from the internet to accomplish generic tasks is okay - for example, a line of code that replaces a character at a specific position in a string.

A printable version of the project requirements can be found [here](./assets/project-requirements.pdf).

## Technical requirements

> ✅ More than 2 items marked incomplete in this section will result in the project receiving a failing grade.

Your Application must have the following functionality:

1. The project must be committed to a version control system with clear commit messages reflecting progress.
2. The application must use a `.env` file to securely store configuration variables (Ex: `AWS_ACCESS_KEY_ID`, `AWS_SECRET_ACCESS_KEY`).
3. The project must follow a modular structure with separate folders for services, models, and controllers.
4. The database connection logic must be in a `services/database.js` file.
5. The app must connect to a `DynamoDB` instance using the `AWS` `SDK`.

The following RESTful API routes must be implemented and functional:

1.  GET /resources – Retrieve all resources.
2.  GET /resources/:id – Retrieve an resource by ID.
3.  POST /resources – Create a new resource.
4.  PUT /resources/:id – Update an resource by ID.
5.  DELETE /resources/:id – Delete an resource by ID.

6.  The app must include a Dockerfile to containerize the application.
7.  The Docker container must expose port 3000 and use environment variables for configuration.

## Code convention and UI/UX requirements

> ✅ More than three items marked incomplete in this section will result in the project receiving a failing grade.

- The code must be well-organized and modular, with functions handling specific tasks.
- The code should follow Javascript best practices and be well-documented with comments where necessary.
- The terminal interface must be user-friendly and intuitive, with clear prompts and instructions.
- The application must validate user input to ensure that it is correct and within expected parameters.
- Error messages should be clear and informative, guiding users to correct their input.

## README requirements

> ✅ More than two items marked incomplete in this section will result in the project receiving a failing grade.

- The app's name.
- A brief description of your app and its functionality.
- A _Getting started_ section. This section should include instructions on how to interact with your app.
- A _Technologies used_ section. This section should list the principal technologies used by your application, for example, Javascript and any major frameworks or libraries.
- If necessary, an _Attributions_ section. This section should include links to any external resources (such as libraries or assets) you used to develop your application that require attribution. You can exclude this section if it does not apply to your application.

## Evaluation

Your instructional team will evaluate your project after the project's due date. Your instructors will use the above guidelines to determine whether or not your project meets all of the minimum requirements.

If there is a specific section of code that you would like an instructor to provide additional feedback on, please ask!

## Guidance

### Getting started

Here are some quick tips to get your project started:

- Discuss your app idea with an instructor to get feedback before you dive too deep into planning.
- **_Keep it simple._** Minimum Viable Product (MVP) functionality that works well is better than extra functionality added to an app with bugs
- Prioritize and implement functionality step-by-step, one at a time. Develop features in a way that allows you to test as you go - try your best to follow the flow of data through your app.
- Regularly review the project requirements to ensure you're on track to pass the project. A printable version of the project requirements can be found [here](./assets/project-requirements.pdf).
- Add comments to your code where it makes sense to do so. Most code is self-documenting, and you shouldn't add comments explaining the obvious. Ideally, comments should explain the **_why_** of code where it's necessary.

### Project assistance

Your instructor team will provide guidelines for reaching out for help during the project.
