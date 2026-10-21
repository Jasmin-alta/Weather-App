# ☀️ Weather App

A responsive weather application built using **HTML, CSS, JavaScript, and the OpenWeatherMap API**. Users can search for a city and view real-time weather information through a simple, user-friendly interface.

## 🌤️ Features

- **City Search:** Search for weather information by entering a city name.
- **Real-Time Weather Data:** Retrieve current weather conditions using the OpenWeatherMap API.
- **Temperature Display:** View temperatures in Celsius.
- **Humidity & Wind Speed:** Display additional weather information.
- **Dynamic Weather Icons:** Automatically update weather icons based on current conditions.
- **Error Handling:** Display an error message when an invalid city is entered.

## 🛠️ Technologies Used

- **HTML5:** Structures the application's interface.
- **CSS3:** Styles the application and its layout.
- **JavaScript:** Handles user interactions, API requests, and dynamic content updates.
- **OpenWeatherMap API:** Provides current weather data.
- **Vite:** Development server and environment variable configuration.
- **Git & GitHub:** Version control and project hosting.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Jasmin-alta/Weather-App.git
cd Weather-App
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Your API Key

Create a `.env` file in the project's root directory and add your OpenWeatherMap API key:

```env
VITE_API_KEY=your_api_key_here
```

You can obtain an API key from [OpenWeatherMap](https://openweathermap.org/api).

### 4. Run the Application

```bash
npm run dev
```

Open the local URL displayed in your terminal (usually `http://localhost:5173/`).

## 💻 How It Works

1. The user enters a city name into the search bar.
2. JavaScript sends a request to the OpenWeatherMap API using `fetch()`.
3. The API returns weather data in JSON format.
4. JavaScript extracts the temperature, humidity, wind speed, and weather conditions.
5. The application dynamically updates the interface with the results.

## 📚 What I Learned

Through this project, I gained hands-on experience with:

- Fetching and processing data from external APIs using asynchronous JavaScript (`async/await`).
- Working with JSON responses.
- Using DOM manipulation to update webpage content.
- Implementing event listeners for user interactions.
- Handling API responses and invalid user inputs.
- Configuring environment variables with Vite.
- Using Git and GitHub to manage and share a project.

## 🔐 API Key Configuration

The `.env` file is excluded from Git using `.gitignore`.

**Note:** Environment variables prefixed with `VITE_` are exposed in the client-side application. This setup prevents accidental commits of the `.env` file but does not keep the API key secret from users.

## 👩‍💻 Author

**Jasmin Altamirano**

[GitHub](https://github.com/Jasmin-alta)

---

*Built as a personal project to strengthen my JavaScript, API integration, and frontend development skills.*
