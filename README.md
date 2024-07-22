Sure! Here's the updated README file including the additional details and deployment link:

---

# WorkoutWizard

## Overview

WorkoutWizard is a comprehensive React application designed to assist users in their fitness journey by providing personalized workout plans and tracking their fitness progress. This project leverages various APIs to offer exercise recommendations, nutritional advice, and progress tracking features, creating an engaging and user-friendly fitness experience.

## Features

- **Personalized Workout Plans**: Generates customized workout plans based on user preferences and fitness goals.
- **Comprehensive Exercise Library**: Displays exercises sorted by body part, includes animated exercise demonstrations, details targeted muscle groups, and shows related YouTube videos for correct form. Suggests alternative exercises.
- **Progress Tracking**: Allows users to log workouts and track their fitness progress over time.
- **Nutritional Advice**: Offers dietary recommendations to complement workout routines.
- **Firebase Authentication**: Supports user authentication with Firebase, including Google login.
- **Responsive Design**: Ensures a seamless user experience across devices.

## Technologies Used and Skills Demonstrated

- **React**: For building the user interface.
- **HTML & CSS**: For structuring and styling the app.
- **Firebase**: For real-time database management and user authentication.
- **Google Login**: For easy user authentication and login.
- **React Router**: For managing navigation within the app.
- **Axios**: For making API requests.
- **YouTube Data API**: For fetching exercise demonstration videos.
- **Git**: For version control.

## Installation

To get started with WorkoutWizard, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/WorkoutWizard.git
   cd WorkoutWizard
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Run the Application**:
   ```bash
   npm start
   ```

4. **Open in Browser**:
   Navigate to `http://localhost:3000` to see the app in action.

## Deployment

You can access the live version of the app at the following link:
[https://workout-wizard-gules.vercel.app/](https://workout-wizard-gules.vercel.app/)

## API Integration

WorkoutWizard integrates with multiple fitness and nutrition APIs to fetch real-time data. Ensure you have the necessary API keys and endpoints configured in the project.

1. **Configure API Keys**:
   Create a `.env` file in the root directory and add your API keys:
   ```plaintext
   REACT_APP_API_KEY=your_api_key_here
   REACT_APP_API_ENDPOINT=your_api_endpoint_here
   ```

2. **Fetch Data**:
   The application uses Axios to make HTTP requests to the configured APIs and retrieves the latest data.

## Project Structure

```plaintext
WorkoutWizard/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── WorkoutPlan.js
│   │   ├── ExerciseDetail.js
│   │   └── ...
│   ├── utils/
│   │   ├── api.js
│   │   └── ...
│   ├── App.js
│   ├── index.js
│   └── ...
├── .env
├── package.json
└── README.md
```

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, feel free to contact:

- **Name**: Paritosh Saini
- **Email**: sainiparitosh6@gmail.com

---

Feel free to customize any part of this README to better fit your project's specifics.
