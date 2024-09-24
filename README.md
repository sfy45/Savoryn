
# SAVORYN - A Food Waste Reduction Platform

## Overview
The Food Waste Reduction Platform is an application designed to connect restaurants, households, and supermarkets with surplus food or grocery items to those in need. 
By facilitating the sale or donation of food items nearing their shelf life, this platform aims to reduce food waste and provide support to food banks, low-budget individuals, and donation organizations.

## Features
- **User Registration**: Create an account as a distributor or a recipient.
- **Surplus Food Listings**: Distributors can list surplus food or grocery items for sale or donation.
- **Point System**: Users distributing food earn points, which can be redeemed for food or donated.
- **Search Functionality**: Easily search for available surplus food items based on location and category.
- **Real-Time Notifications**: Get notifications for new listings and point redemption opportunities.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask/Django)
- **Database**: SQL
- **Cloud Provider**: Google Cloud
- **APIs**: Integration with Google Calendar and/or Recipe APIs

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/sfy45/FoodWasteReductionPlatform.git
   ```

2. Navigate to the project directory:
   ```bash
   cd FoodWasteReductionPlatform
   ```

3. Install the required dependencies (Python):
   ```bash
   pip install -r requirements.txt
   ```

4. Set up the database:
   - Configure the database connection in the `config.py` file.
   - Run the migration scripts to create the necessary tables.

5. Start the application:
   ```bash
   python app.py
   ```

## Usage
1. Open your browser and go to `http://localhost:5000`.
2. Sign up or log in to your account.
3. Browse available surplus food items or list your own.
4. Earn points by distributing food and redeem them for rewards.

## API Integration
This project integrates with the following APIs:
- **Google Calendar API**: For scheduling notifications and reminders related to food distribution.
- **Recipe API**: For suggesting recipes based on the available food items.

## Contributing
Contributions are welcome! If you have suggestions for improvements or want to report bugs, please create an issue or submit a pull request.


## Contact
For inquiries or feedback, please reach out to me at:
- Email: sophiasad1421@gmail.com
- GitHub: [sfy45](https://github.com/sfy45)
``` 

## Note: This is a sample front-end interface developed for demonstration purposes, and the project will be further enhanced over time. Thank you!
