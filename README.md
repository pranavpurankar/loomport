# Shipment Trip Validation System

This project is a **Shipment Trip Validation System** that allows users to input and validate trips related to shipments with multiple pickup, dropoff, and warehouse locations.

## **Features**
- Users can add trips with pickup, dropoff, and optional warehouse locations.
- Data is persisted in the browser using **localStorage**.
- **Trip validation** is performed by calling a mock API (Mockaroo).
- A secondary **About Us** page provides more information about the application.

## **Project Structure**
- **index.html**: Main page where users input trip details.
- **about.html**: Secondary page providing explanations about the app.
- **style.css**: Stylesheet with dark theme and responsive design.
- **js/app.js**: Handles trip adding, localStorage, and validation logic.
- **js/trip.js**: Contains the logic for handling trips and shipment data.
- **js/validator.js**: Validates the trips through API calls.

## **How to Run**
1. Open `index.html` in a browser.
2. Add trips by entering pickup, dropoff, and warehouse locations.
3. Click **Add Trip** to save each trip to localStorage.
4. Click **Validate Trips** to check the validity of the trips.
5. Navigate to the **About Us** page for additional information.

## **Technologies Used**
- **HTML5** and **CSS3** for structure and design.
- **JavaScript (ES6)** modules for functionality.
- **localStorage** for persistent data storage.
- **Mockaroo API** for validating trips.

## **API**
The app uses **Mockaroo** to validate trip data. Mockaroo generates a mock API with random data for testing purposes.

## **UI Design**
- The app has a **dark theme** with a clean, minimalist design.
- A **logo** is displayed at the top of the page.
- Navigation between pages is simple and intuitive.

## **License**
This project is open-source and free to use.
