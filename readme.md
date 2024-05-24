# Tourist Reservation

Welcome to Tourist Reservation, a dynamic tour booking app developed as part of my Backend Development course. This project involved creating a comprehensive platform for booking and managing tours, integrating secure payment systems, and providing a seamless user experience.

## About the App

Tourist Reservation is designed to make exploring and booking tours easy and convenient. With a range of features, users can find, book, and manage tours with just a few clicks. Below are the main features and technologies used in the development of this application.

### Features

- **Sign Up / Log In**: Users can create an account or log in using sample credentials (email: test@example.com, password: test1234).
- **Add Profile Picture**: Users can personalize their profiles by uploading a profile picture.
- **Update Password**: Users can change their password to keep their accounts secure.
- **Change Email and Name**: Users can update their profile information.
- **View Tours**: Users can browse a wide range of exciting tours.
- **Book Tours**: Users can book tours easily. Use the credit card number 4242 4242 4242 4242 with any future date and CVV for sample transactions.
- **Check Your Bookings**: Users can view their booking history from their profile.

### Technical Details

- **Frontend**: Developed with React for a dynamic and responsive user interface, and React Query for efficient data synchronization.
- **State Management**: Utilized Context API for global state management, ensuring a smooth and cohesive user experience.
- **Backend**: Built with Node.js, Express, and Mongoose for a robust and scalable server-side framework.
- **Database**: Leveraged MongoDB for its flexibility and powerful querying capabilities, ideal for handling diverse tour data.
- **Payment Gateway**: Integrated Stripe for secure online payments.
- **Email System**: Implemented with Brevo SMTP for handling email functionalities.

## Project Setup

### Documentation

For detailed API documentation, visit: [Postman Documentation](https://lnkd.in/drDk4qp6)

### Key Functionalities

- **Authentication**: User registration, login, JWT authentication, and email confirmation.
- **User Management**: Profile photo upload, update user information, and password reset functionalities.
- **Tour Management**: Browse, book, and manage tours.
- **Payment System**: Secure payments integrated with Stripe.
- **Architecture**: Follows the MVC architecture for a clean and organized codebase.
- **Protected Routes**: Ensures only authenticated users can access certain routes.
- **Form Validation**: Robust validation for user inputs.

## Technologies Used

- **Node.js**
- **Express**
- **MongoDB**
- **Mongoose**
- **React**
- **React Query**
- **Context API**
- **Stripe**
- **Brevo SMTP**
- **Pug.js**

## Getting Started

To get a local copy up and running, follow these simple steps:

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/tourist-reservation.git
   ```
2. Navigate to the project directory:
   ```sh
   cd tourist-reservation
   ```
3. Install the dependencies:
   ```sh
   npm install
   ```
4. Set up environment variables by creating a `.env` file in the root directory and adding the following:
   ```env
   NODE_ENV=development
   DATABASE=mongodb+srv://<your-database-url>
   JWT_SECRET=<your-jwt-secret>
   JWT_EXPIRES_IN=90d
   EMAIL_USERNAME=<your-email-username>
   EMAIL_PASSWORD=<your-email-password>
   EMAIL_HOST=<your-email-host>
   STRIPE_SECRET_KEY=<your-stripe-secret-key>
   ```

### Usage

1. Start the development server:
   ```sh
   npm run dev
   ```
2. Open your browser and visit `http://localhost:3000`.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
