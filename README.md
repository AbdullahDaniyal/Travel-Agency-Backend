# Travel-Agency-Backend
This repository contains the backend code for a comprehensive travel agency portal. The portal is designed to cater to various stakeholders in the travel industry, including travelers, travel agencies, hotel owners, and a super admin. Each panel has distinct functionalities tailored to its specific role.
## Description
The portal is divided into four main panels:
### Traveller Panel: 
Allows travelers to browse travel packages, hotels, view ratings, and send/receive feedback. Users can comment, rate services, and customize their user profiles.
### Super Admin Panel: 
Empowers administrators to oversee the entire operation. Features include advanced data visualizations using Chart.js, integration of a weather API for real-time weather updates, and managing user roles and permissions.
### Travel Agency Panel: 
Designed for travel agencies to manage their offerings, view bookings, and interact with customers.
### Hotel Owner Panel: 
Allows hotel owners to manage their listings, view booking statistics, and interact with both travelers and travel agencies.

The backend is built using MongoDB, Express, and Node.js (MEN stack). It features integration with Cloudinary for image uploads, Etherscan for fake SMTP email handling, and Three.js for advanced graphical representations.
## Features
1. User authentication and authorization.
2. CRUD operations for travel packages, hotel listings, and user profiles.
3. Real-time weather updates in the Super Admin Panel.
4. Advanced data visualization for analytics in the Super Admin Panel.
5. Image upload functionality with Cloudinary.
6. Etherscan integration for email testing purposes.
7. Interactive 3D graphics with Three.js.
## Installation
Clone the repository and install dependencies:
git clone [URL-of-Your-GitHub-Repository]
cd [Your-Project-Folder]
npm install
## Usage
To start the server, run:
npm start
Ensure MongoDB is running on your machine or use a cloud-based MongoDB service.
## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
