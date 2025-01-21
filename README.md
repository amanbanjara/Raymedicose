# Online Medical Store    
 
An efficient and user-friendly web application designed to streamline the purchase and management of medicines and healthcare products online. This project serves as a one-stop solution for customers, pharmacies, and administrators.

## Features

### For Customers:
- **Browse and Search Products:** Search for medicines and healthcare products by name, category, or symptoms.
- **Add to Cart:** Add desired products to a virtual shopping cart.
- **Online Payment:** Secure payment gateways for hassle-free transactions.
- **Order History:** Track past orders and reorder with ease.

### For Pharmacies:
- **Inventory Management:** Update stock levels and product details.
- **Sales Reports:** View detailed reports of orders and revenue.

### For Admins:
- **User Management:** Manage customer and pharmacy profiles.
- **Product Listings:** Approve or edit product listings.
- **Analytics:** Monitor platform activity and performance.

## Technology Stack

- **Frontend:** HTML, CSS,JavaScript, ReactJS
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Payment Gateway:** Stripe/PayPal integration

## Setup and Installation

### Prerequisites:
- Node.js and npm installed
- MongoDB server setup

### Steps to Run Locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Ray-medical-store.git
   ```

2. Navigate to the project directory:
   ```bash
   cd online-medical-store
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up environment variables:
   Create a `.env` file in the root directory and include the following:
   ```env
   MONGO_URI=your_mongodb_connection_string
   PORT=5000
   STRIPE_SECRET_KEY=your_stripe_secret_key
   ```

5. Start the application:
   ```bash
   npm start
   ```

6. Open your browser and visit `http://localhost:5000`.

## Contribution Guidelines

We welcome contributions from the community. To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of your changes"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For inquiries or support, please contact:
- **Email:** support@medicalstore.com
- **GitHub Issues:** [Open an issue](https://github.com/your-username/online-medical-store/issues)

## Screenshots

![Homepage](./screenshots/homepage.png)
![Product Page](./screenshots/product-page.png)

## Future Enhancements

- Implement AI-based medicine recommendations.
- Add multi-language support.
- Develop a mobile application version.

--

Happy Coding! 🚀
