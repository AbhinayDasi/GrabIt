GrabIt
GrabIt is an online platform designed to streamline the process of ordering and pre-ordering food within a campus. It offers a user-friendly interface for students and staff to place their orders from various campus eateries efficiently. Where the staffs and students can be used within the campus.

Features
Order & Pre-order Food: Easily place orders or schedule pre-orders from your favorite campus eateries.
User-Friendly Interface: A clean and intuitive interface built with React.js for seamless user experience.
Real-Time Updates: Get real-time updates on your order status.
Secure & Scalable: Robust backend built with Node.js and Express.js ensuring secure and scalable operations.
Image Management: Integrated with Cloudinary for efficient image management and storage.
Database: MongoDB is used for storing user and order information securely.
Technologies Used
Frontend: React.js
Backend: Node.js, Express.js
Database: MongoDB
Image Management: Cloudinary
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/GrabIt.git
cd GrabIt
Install dependencies for both frontend and backend:
bash
Copy code
# For backend
cd backend
npm install

# For frontend
cd ../frontend
npm install
Configure environment variables:
Create a .env file in the backend directory with the following variables:

plaintext
Copy code
MONGO_URI=your_mongodb_uri
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
Run the application:
bash
Copy code
# Start backend server
cd backend
npm start

# Start frontend server
cd ../frontend
npm start
Usage
Navigate to the frontend URL (typically http://localhost:3000).
Register or log in to your account.
Browse the available food options and place your order or pre-order.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

License
This project is licensed under the MIT License.

