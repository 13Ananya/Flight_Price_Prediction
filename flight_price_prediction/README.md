# Flight Price Prediction

## Overview
The **Flight Price Prediction** project is designed to predict airline ticket prices based on multiple input parameters such as origin, destination, date, and airline. This application provides users with an interactive interface to enter their travel details and receive an estimated ticket price using a trained machine learning model.

## Features
- **Flight Price Prediction**: Uses machine learning to estimate ticket prices based on user input.
- **User-Friendly UI**: Developed using ReactJS and styled with Tailwind CSS.
- **Flask API Integration**: The trained model is deployed on a Flask backend, serving predictions via a REST API.
- **Model Retraining Support**: Can be updated with new datasets to improve accuracy.
- **Responsive Design**: Ensures compatibility across different devices and screen sizes.

## Tech Stack
### Frontend
- **ReactJS** - User interface development
- **Tailwind CSS** - Modern, responsive design styling
- **Vite** - Fast development server and build tool

### Backend
- **Python** - Core programming language for model training and backend logic
- **Flask** - API framework to serve model predictions
- **scikit-learn** - Machine learning library for model training and prediction

### Additional Tools
- **PostCSS** - CSS processing tool
- **ESLint** - Code linting and formatting
- **Git** - Version control

## File Structure
```
flight_price_prediction/
│── envflight/               # Virtual environment (not included in repository)
│── node_modules/            # Dependencies for frontend
│── public/                  # Static assets
│── src/                     # Source code
│   ├── assets/              # Images and assets
│   ├── App.css              # Global styles
│   ├── App.jsx              # Main React component
│   ├── index.css            # Styles for index
│   ├── main.jsx             # Entry point for React
│── .gitignore               # Ignored files for Git
│── eslint.config.js         # ESLint configuration
│── index.html               # Main HTML file
│── package-lock.json        # Dependency lock file
│── package.json             # Dependencies and scripts
│── postcss.config.js        # PostCSS configuration
│── README.md                # Project documentation
│── tailwind.config.js       # Tailwind CSS configuration
│── vite.config.js           # Vite configuration
│── Screenshots/             # Folder for project images
│── app.py                   # Flask backend API
│── Flight_Price_Prediction.ipynb  # Jupyter Notebook for model training
│── Flight.csv               # Dataset file
│── model.pkl                # Trained machine learning model
```

## Dataset
The model is trained using the dataset available on Kaggle:
[Flight Price Prediction Dataset](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- **Node.js & npm** (for running the frontend)
- **Python & pip** (for running the backend)

### Clone the Repository
```sh
git clone https://github.com/13Ananya/Flight_Price_Prediction.git
cd flight_price_prediction
```

### Backend Setup
1. Navigate to the root directory:
   ```sh
   cd flight_price_prediction
   ```
2. Create a virtual environment and activate it:
   ```sh
   python -m venv envflight
   source envflight/bin/activate  # On Windows use `envflight\Scripts\activate`
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the Flask API:
   ```sh
   python app.py
   ```

### Frontend Setup
1. Navigate to the `src` directory:
   ```sh
   cd src
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React app:
   ```sh
   npm run dev
   ```

The application should now be accessible at `http://localhost:3000/`.

## Usage
1. Open the application in your browser.
2. Enter flight details such as origin, destination, date, and airline.
3. Click the "Predict" button.
4. The estimated ticket price will be displayed below the form.

## Future Enhancements
- **Real-Time Data Integration**: Fetch live pricing data from airline APIs.
- **Advanced Machine Learning Models**: Implement deep learning techniques for better accuracy.
- **User Authentication**: Enable users to save searches and track prices.
- **Cloud Deployment**: Deploy the app on AWS, Heroku, or Vercel for public access.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the **MIT License**.

## Contact
For any queries or suggestions, please reach out via:
- **GitHub**: [13Ananya](https://github.com/13Ananya)
- **Dataset Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)

---
Developed with ❤️ by [13Ananya](https://github.com/13Ananya)

