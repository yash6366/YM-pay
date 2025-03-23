YM-pay-main/
├── client/                 # React frontend
│   ├── src/
│   │   ├── pages/         # React components for different pages
│   │   │   ├── home.js    # Landing page
│   │   │   ├── Login.js   # User login
│   │   │   ├── Signup.js  # User registration 
│   │   │   └── transation.js # Transaction management
│   │   └── App.js         # Main React component
├── server.js              # Express backend server
├── .env                   # Environment variables
└── package.json          # Project dependencies			

Key Features
User authentication (login/signup)
Digital wallet functionality
Real-time transaction processing
Transaction history tracking
Interactive transaction graphs
UPI-based payment system

Tech Stack
Frontend: React.js, Bootstrap, Recharts
Backend: Node.js, Express
Database: MongoDB Atlas
Authentication: Basic email/password
API: RESTful API endpoint

Key Features
User authentication (login/signup)
Digital wallet functionality
Real-time transaction processing
Transaction history tracking
Interactive transaction graphs
UPI-based payment system

Tech Stack
Frontend: React.js, Bootstrap, Recharts
Backend: Node.js, Express
Database: MongoDB Atlas
Authentication: Basic email/password
API: RESTful API endpoint

Main Components

User Management:
Registration with auto-generated UPI ID
Login system
Balance tracking

Transaction System:
Send money between users
Transaction history
Real-time balance updates

Dashboard:
Current balance display
Transaction visualization
Transaction listing

API Endpoints:
/api/signup - User registration
/api/login - User authentication
/api/transaction - Process transactions
/api/transactions/:upi_id - Get transaction history
/api/user/:upi_id - Get user details

Environment Setup:
MongoDB connection string configured
Server running on port 5000
Frontend running on port 3000

Note: The project uses a MongoDB Atlas cluster for database operations and includes environment variables for configuration.
