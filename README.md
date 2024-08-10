# Quiz App

## Overview

This is a simple quiz application built using React for the frontend and deployed on AWS Amplify. User authentication and authorization are handled by Amazon Cognito.

![Screenshot from 2024-08-09 19-30-22](https://github.com/user-attachments/assets/e1ee48c7-f25d-45bd-93e6-4f571bc30e80)

## Features

User authentication and authorization using Amazon Cognito

Static quiz questions and answers

Basic quiz functionality (start, answer, score)

Deployment on AWS Amplify for hosting

## Technologies Used

React

AWS Amplify

Amazon Cognito

## Prerequisites

Node.js and npm (or yarn) installed

AWS account with Amplify and Cognito configured

Basic understanding of React, AWS Amplify, and Amazon Cognito

## Getting Started

Clone the repository:

``` bash
git clone https://github.com/vijaymehrotra/amplify-cognito-quiz.com

cd amplify-cognito-quiz

npm install
```

## Configure AWS Amplify:

Follow the AWS Amplify documentation to set up your project and configure authentication with Amazon Cognito.

Replace the placeholder values in the src/App.js file with your Cognito configuration details.

## Run the development server:

``` bash
npm start
```

## Deploy to AWS Amplify:
![Screenshot from 2024-08-09 19-25-49](https://github.com/user-attachments/assets/dd9d86f3-56a8-45a7-93cf-21d5b2d3fdd9)


Follow the AWS Amplify documentation to deploy your application.

## Project Structure
![Screenshot from 2024-08-09 23-32-35](https://github.com/user-attachments/assets/567be1ef-fdc1-481b-aa6e-7820c0260279)


src: Contains the React components, styles, and other project files.

public: Contains the index.html file and other static assets.

## Notes

This project uses static quiz data. For a more dynamic experience, consider using a database or API to fetch quiz questions.

Enhance the user experience by adding features like time limits, difficulty levels, and user profiles.

Implement error handling and user feedback mechanisms for a robust application.

https://github.com/user-attachments/assets/e6e21e58-fbfa-4568-980c-d8a799798dc3

## Contributing

Contributions are welcome! Please feel free to fork the repository and submit pull requests.
