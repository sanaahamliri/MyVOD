# MyVOD Mobile Application

## Project Overview
MyVOD is a native mobile application built with React Native, allowing users to sign up, log in, stream movies, and manage their personal information. This application includes features for secure user authentication, streaming of films, user interactions like rating and commenting on films, and managing a favorites list.

## Features
### Users
- **User Registration**: Allows users to create an account.
- **Login and Subscriber Management**: Secure authentication with account management for subscribed users.

### Streaming and Interactions
- **Movie Streaming**: Access to the movie catalog for subscribed users.
- **Movie Rating**: Users can rate movies.
- **Search and Filtering**: Search movies by name and filter them by genre and date.

### Comments and Favorites
- **Comments**: Add comments on movies and display associated comments for each movie.
- **Favorite Movies**: Users can manage a list of their favorite movies.

### Content and Suggestions
- **Displaying New Movies**: Showcase the latest movies added on the homepage.
- **Movie Details**: Detailed information about each movie with related movie suggestions.

### Administration
- **Admin Interface**: User management and usage statistics analysis, such as:
  - Time spent on the application.
  - Number of visitors.
  - Number of registrations overall and within a given period.

### Notifications
- **Scheduled Notifications**: Types of notifications include:
  - Sending notifications to users who have not opened the application for more than 24 hours.
  - Real-time notifications for new movie additions.
  - Promotional alerts for movies on sale.
  - Subscription renewal reminders.

### Payment and Verification
- **Credit Card Payment**: Implementation of a secure credit card payment template.
- **Card Verification Service**: Integration of an algorithm based on Luhn to validate credit card numbers.

## Technologies Used
- **Mobile Frontend**: React Native, Expo
- **Backend**: NestJS, TypeORM
- **Testing**: Jest, Supertest, React Native Testing Library

## Installation
1. Clone the repository:
    ```sh
    git clone  https://github.com/sanaahamliri/MyVOD.git
    cd myvod
    ```
2. Install dependencies:
    ```sh
    npm install
    ```
3. Start the development server:
    ```sh
    npm start
    ```

## Usage
1. Register a new user account.
2. Log in with your credentials.
3. Browse the movie catalog and start streaming.
4. Rate, comment, and add movies to your favorites list.

## Testing
Run the tests using:
```sh
npm test
