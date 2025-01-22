# Restaurant Website

Welcome to the Restaurant Website project! This repository contains the source code for a responsive and modern restaurant website, designed to showcase menu items, services, facilitate online reservations, enable secure online payments, and manage content through an admin interface.

## Features

- **Responsive Design**: Ensures optimal viewing experience across various devices.
- **Menu Display**: Showcases the restaurant's offerings with descriptions and pricing.
- **Online Reservations**: Allows customers to book tables directly through the website.
- **Payment Gateway Integration**: Securely accepts payments for reservations or orders using a reliable payment gateway.
- **Dual Authentication System**:
  - **Admin Login**: Allows the admin to manage website content, bookings, and settings.
  - **User Login**: Enables customers to access their reservation details and make bookings.
- **Content Management**: Admins can update menu items, contact details, and manage reservations.
- **Contact Information**: Provides easy access to location, contact details, and operating hours.

## Technologies Used

- **HTML5**: For structuring the web pages.
- **CSS3**: For styling and layout.
- **JavaScript**: For interactive elements and form validations.
- **Bootstrap**: For responsive design and pre-built components.
- **Node.js / Express.js**: Backend framework for server-side logic and routing.
- **MongoDB**: Database for storing user data, reservations, and site content.
- **Authentication Library**: For secure login functionality (e.g., Passport.js).
- **Payment Gateway API**: Integrated to handle secure online payments.

## Getting Started

To get a local copy up and running, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Akii017/Restaurant_Website.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd Restaurant_Website
   ```
3. **Install Dependencies**:
   ```bash
   npm install
   ```
4. **Set Up Environment Variables**:
   - Create a `.env` file in the root directory.
   - Add the following:
     ```env
     DB_URI=your_mongodb_connection_string
     PAYMENT_API_KEY=your_payment_gateway_api_key
     ADMIN_EMAIL=admin_email
     ADMIN_PASSWORD=admin_password
     ```
5. **Run the Application**:
   ```bash
   npm start
   ```
6. **Access the Website**:
   - Visit `http://localhost:3000` in your browser.

## Admin and User Authentication

### Admin Login
- **Role**: Manage bookings, update site content, and configure settings.
- **Access**: Admins have exclusive rights to:
  - Add, update, or remove menu items.
  - View, confirm, or cancel bookings.
  - Update contact information and operating hours.

### User Login
- **Role**: Book tables, make payments, and view personal bookings.
- **Access**: Users can:
  - View the menu and make reservations.
  - Access their booking history.
  - Update personal information.

## Payment Gateway Integration

This project includes integration with a payment gateway for secure transactions. To configure the payment gateway:

1. Sign up for a payment gateway provider (e.g., Stripe, PayPal, Razorpay).
2. Obtain your API keys from the provider.
3. Update the `.env` file with the keys.
4. Test payment integration in a sandbox environment before deploying to production.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, please contact:

- **Name**: Akhil Vijayan
- **Email**: akhilv172004@gmail.com

---

Thank you for visiting the Restaurant Website project! We hope this template helps you create an engaging online presence for your restaurant.
