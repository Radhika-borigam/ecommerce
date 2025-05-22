Multi-Vendor E-commerce Platform
A full-stack e-commerce platform that supports multiple vendors, built with Spring Boot and React.

🌟 Features
For Customers
User authentication and authorization
Product browsing and searching
Shopping cart management
Order placement and tracking
Review and rating system
Wishlist functionality
AI-powered chatbot for product recommendations
Secure payment integration
For Sellers
Seller dashboard
Product management
Order management
Revenue tracking
Payment processing
Analytics and reporting
For Admins
User management
Seller verification
Category management
Coupon management
Deal management
Platform analytics
🛠️ Tech Stack
Backend
Java Spring Boot
Spring Security with JWT
MySQL Database
JPA/Hibernate
RESTful APIs
Frontend
React with TypeScript
Redux Toolkit for state management
Material-UI components
Formik for forms
Axios for API calls
Infrastructure
Docker containerization
MySQL for database
Nginx for frontend serving
🚀 Getting Started
Prerequisites
Docker and Docker Compose
Node.js (for local development)
Java 17 (for local development)
MySQL (for local development)
Running with Docker
Clone the repository
git clone https://github.com/Radhika-borigam/multi-vendor-ecommerce-website.git
cd multi-vendor-ecommerce-website
Start the application using Docker Compose
docker compose up --build
The application will be available at:

Frontend: http://localhost:3001
Backend: http://localhost:8080
Database: localhost:3306
Local Development Setup
Backend
Navigate to the backend directory
cd source\ code/backend-spring\ boot
Build the project
./mvnw clean install
Run the application
./mvnw spring-boot:run
Frontend
Navigate to the frontend directory
cd source\ code/fontend-react
Install dependencies
npm install
Start the development server
npm start
📝 Environment Variables
Backend
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_multi_vendor
spring.datasource.username=root
spring.datasource.password=your_password
Frontend
REACT_APP_API_URL=http://localhost:8080
🔐 Security
JWT based authentication
Password encryption
CORS configuration
Secure payment processing
Input validation and sanitization
📦 Database Schema
The application uses MySQL with tables for:

Users/Customers
Sellers
Products
Orders
Cart Items
Reviews
Categories
Transactions
Wishlist Items
🤝 Contributing
Fork the repository
Create your feature branch (git checkout -b feature/YourFeature)
Commit your changes (git commit -m 'Add some feature')
Push to the branch (git push origin feature/YourFeature)
Open a Pull Request
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

👥 Authors
Radhika Borigam - GitHub Profile
