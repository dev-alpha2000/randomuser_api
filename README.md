## Overview

This project is a Random User API app built using React. The app fetches random user data from the Random User API and displays information such as name, picture, email, and location. It allows users to refresh the data to get new random users.

## Features

Fetch Random Users: Fetch and display random user data such as name, email, phone number, and location.

User Details: Display user information including profile picture, gender, nationality, and address.

Load More Users: Option to load more users or refresh the current user list.

Responsive Design: The app is fully responsive and works seamlessly across mobile, tablet, and desktop devices.

Error Handling: Graceful handling of API errors or failed requests.

## Installation
To run this project locally, follow these steps:

Clone the repository:

bash code

git clone https://github.com/yourusername/random-user-api-app.git
cd random-user-api-app

Install the dependencies:

bash code
npm install
Start the development server:

bash code
npm start
The app will be available at http://localhost:3000.

## Usage

View Random Users: The app will display random user data fetched from the Random User API on initial load.

Load More Users: Click the "Load More" button to fetch more random users from the API.

User Details: Each user card will display detailed information including their name, email, phone, and location.


Error Handling: If the API request fails, an error message will be displayed.

## Customization

API Data: Customize the data fetched from the Random User API by modifying the request in the api/ folder (e.g., to include or exclude certain fields like date of birth, gender, or nationality).

Styling: Update the styles in App.css to change the design and layout of the user cards or the overall app.

Pagination: Add pagination or infinite scroll to fetch a batch of users as the user scrolls down the page.

Filters: Implement filtering by nationality, gender, or other user attributes using the API’s filtering options.

## Example
When you open the app:

The app automatically fetches random user data from the Random User API.

Each user card displays the user's profile picture, name, email, phone number, and address.

Users can click the "Load More" button to fetch additional random users.

## Dependencies

React: Frontend framework for building the UI.

Axios: For making API requests to the Random User API.

CSS or Styled Components: For styling the app.
