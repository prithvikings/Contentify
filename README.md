# Article Summarizer

## Live Link 

https://sumz-gpt-4.netlify.app/

Welcome to Contentify! This project aims to revolutionize content creation by providing a user-friendly and efficient platform for creating various types of content, ranging from articles and blogs making them concise to read.


## Tech Stack

**Client:** React, Redux, TailwindCSS

**Server:** Node, Express


## Features

👉 Modern User Interface: A modern and user-friendly interface, offering an intuitive experience for users.

👉 Summary Generation: Users can input the URL of a lengthy article, and the web app utilizes AI to provide a concise summary of the article content.

👉 History Saving with Local Storage: The app includes a history feature, allowing users to save summaries locally, providing a convenient way to revisit and manage their reading history.

👉 Copy to Clipboard Functionality: Enables users to easily share or store the summarized content by copying it to their clipboard.

👉 Advanced RTK Query API Requests: Utilizes the advanced capabilities of Redux Toolkit (RTK) Query for making API requests. These requests fire conditionally based on specific criteria, optimizing data fetching and management.

## Quick Start
Follow these steps to set up the project locally on your machine.

## Prerequisites
Make sure you have the following installed on your machine:


-Git

-Node.js

-npm (Node Package Manager)

Cloning the Repository

## Installation
Install the project dependencies using npm:

```bash
npm install 
```

## Set Up Environment Variables
Create a new file named .env in the root of your project and add the following content:

```bash
VITE_RAPID_API_ARTICLE_KEY=
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on the Rapid API website.

## Running the Project

```bash
npm run dev
```

Open http://localhost:5173 in your browser to view the project.


