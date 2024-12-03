# Winter Clothing Donation

## Purpose

The Winter Clothing Donation web application is designed to help individuals donate winter clothing to people in need across Bangladesh. The platform connects donors with volunteers to ensure that vulnerable communities, especially in rural and low-income areas, can receive much-needed winter clothing during cold weather.

## Live URL

[Winter Clothing Donation - Live](https://winter-clothing-donation-e20cd.web.app/)

## Key Features

- **User Authentication**: Users can register, log in, and manage their profiles.
- **Donation Campaigns**: Browse and donate to various winter clothing campaigns across Bangladesh.
- **Donation Form**: Fill out a form with details of the donated items and pickup location.
- **Responsive Design**: Fully responsive layout for mobile, tablet, and desktop devices.
- **Firebase Integration**: User authentication and data storage powered by Firebase.
- **Toast Notifications**: Confirmation messages on successful donations.

## Technology Stack

- **Frontend**: React.js, CSS (for custom styling), Firebase Authentication, Firebase Firestore.
- **Libraries/Packages Used**:
  - `react-router-dom` for routing
  - `firebase` for authentication and backend
  - `react-toastify` for toast notifications
  - `swiper` for image sliders
  - `daisyUI` for UI components
  - `AOS` (Animate On Scroll) for animations
- **Hosting**: Firebase Hosting

## How to Run the Project Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/winter-clothing-donation.git

   ```

2. Navigate into the project directory:
   cd winter-clothing-donation

3. Install dependencies:
   npm install

4. Add Firebase Configuration:

   - Go to Firebase Console, create a project, and set up Firebase Authentication.
   - Add Firebase config keys to .env file in the root directory:
     REACT_APP_FIREBASE_API_KEY=your-api-key
     REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
     REACT_APP_FIREBASE_PROJECT_ID=your-project-id
     REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket
     REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
     REACT_APP_FIREBASE_APP_ID=your-app-id

5. Start the development server:
   npm start

6. Open your browser and navigate to http://localhost:3000 to see the app.

## Pages and Components

- Home Page: A welcoming page that includes a banner, about section, and donation instructions.
- Donation Campaigns: A page that lists all available campaigns to donate winter clothes.
- Donation Details Page: A private page (only accessible when logged in) where users can fill out a donation form with item details and pickup location.
- Dashboard: A private page that shows the logged-in user's profile information and offers an option to update profile details.
- Login / Registration: Pages for user authentication, including social login via Google.
- Error Page: Displays a 404 error page for invalid routes.

## Challenges Implemented

- Password Toggling: Added functionality to show and hide passwords during user registration.
- Forget Password: Implemented a "Forgot Password" feature to allow users to reset their password.
- Profile Update: Added a feature to update user profile information (Name, Photo URL).
- Animations: Integrated the AOS (Animate On Scroll) package to animate the home page components.

## Future Enhancements

- Email verification after user registration.
- More interactive and detailed donation tracking system.
- Enhanced user experience with additional features like campaign progress tracking.

## Contact Information

If you have any questions or suggestions, feel free to reach out.

- Social Media
- Facebook
- Twitte

## Copyright

© Winter Clothing Donation Website, 2024. All rights reserved.

## License

This project is licensed under the MIT License.

### Points to note:

- Replace `your-username` with your actual GitHub username in the cloning URL.
- The Firebase configuration keys should be inserted into the `.env` file as mentioned in the setup instructions.
- You can adjust the social media links as per your needs or remove them if unnecessary.

This `README.md` file includes details about your project, how to run it, and the technologies used, along with a basic structure and all the necessary information to make it easy for anyone to understand and work with your project.
