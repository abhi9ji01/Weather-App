# Weather App

A simple weather application built with React.js and Vite that displays current weather information for a selected city using the Weather API.

## Features

- Displays current temperature, weather condition, and local time for a selected city.
- Provides weather highlights such as wind status, humidity, visibility, and air pressure.
- Allows toggling between dark and light mode with sun and moon icons.
- Responsive design using Tailwind CSS.

## Getting Started

These instructions will help you set up and run the project on your local machine.

### Prerequisites

Make sure you have Node.js and npm installed on your machine. You can download and install them from [Node.js official website](https://nodejs.org/).

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/abhi9ji01/Weather-App.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd Weather-App
    ```

3. **Install the dependencies**:
    ```bash
    npm install
    ```

4. **Add your Weather API key**:
    - Replace the placeholder apiUrl in `App.jsx` with the actual API key provided by Weather API.

    ```javascript
    const apiUrl = `http://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=${city}&aqi=no`;
    ```

5. **Run the development server**:
    ```bash
    npm run dev
    ```

6. **Open your browser and visit**:
    ```
    http://localhost:5173
    ```

## Usage

- Enter the city name in the input field to get the current weather information for that city.
- Click on the sun or moon icon in the top-right corner to toggle between light and dark mode.

## Built With

- [React.js](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Weather API](https://www.weatherapi.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Font Awesome](https://fontawesome.com/)

## Contributing

Contributions are welcome! Please fork the repository and create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Weather API](https://www.weatherapi.com/) for providing the weather data.
- [Font Awesome](https://fontawesome.com/) for the sun and moon icons.
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework.
## ScreenShots


