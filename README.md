## Weather App (Dynamic Background)

**Description:**

This is a simple weather app built with Node.js, Express, EJS, and the OpenWeatherMap API. It allows users to search for the weather in a specific city and displays the results on a page with a dynamic background.

**Features:**

- **City Search:** Users can enter a city name in a form to get the current weather information.
- **Weather Display:** The app fetches and displays weather data like temperature, description, etc. from the OpenWeatherMap API.
- **Dynamic Background:** The background color changes randomly on page load for a visually appealing experience.
- **Error Handling:** The app handles potential errors during weather data retrieval and gracefully displays a message to the user.

**Installation:**

1. **Clone the repository:**

   ```bash
   git clone https://github.com/aftabmumtaz123/weather-app.git
   ```

2. **Install dependencies:**

   ```bash
   cd weather-app
   npm install
   ```

**Configuration:**

1. **Create a `.env` file:**

   Create a file named `.env` in the project's root directory and add the following line (replace `YOUR_API_KEY` with your actual OpenWeatherMap API key):

   ```
   API_KEY=YOUR_API_KEY
   ```

   **Note:** You can obtain your API key from [https://openweathermap.org/api](https://openweathermap.org/api).

**Usage:**

1. **Start the server:**

   ```bash
   npm start
   ```

   This will start the server on port `3000` by default. You can view the app in your browser at http://localhost:3000/.

2. **Search for weather:**

   Enter the name of a city in the search bar on the app's homepage and press Enter or click the search button. The app will fetch and display the weather data for the entered city with a random background color.

**Additional Notes:**

- This code utilizes the `dotenv` package to securely manage API keys. Make sure you don't commit your `.env` file to your GitHub repository.
- You can customize the EJS templates (`views/weather.ejs`) to change the layout and styling of the app.
- Error handling can be further improved for a more robust user experience.

**License:**

(Consider adding a license to your project, such as MIT or Apache. This helps clarify how others can use and distribute your code.)

**Credits:**

- OpenWeatherMap API ([https://openweathermap.org/](https://openweathermap.org/)) for providing weather data
