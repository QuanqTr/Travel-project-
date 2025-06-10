# Travel Booking System

A full-stack web application for travel and accommodation booking, built with Node.js, Express, MongoDB, and React.

## Project Structure

The project consists of two main parts:
- `api-travel/` - Backend API server
- `travel/` - Frontend React application

### Backend Features

- User authentication with JWT
- Place management (CRUD operations)
- Booking management
- File upload functionality
- MongoDB database integration

### API Endpoints

- **Places:**
  - `GET /places` - Get all places
  - `POST /places` - Create new place
  - `DELETE /places/:id` - Delete a place
  - `PUT /places` - Update place details

- **Bookings:**
  - `POST /bookings` - Create new booking

## Technology Stack

### Backend
- Node.js
- Express.js
- MongoDB
- JWT for authentication
- Multer for file uploads

### Frontend
- React.js
- Tailwind CSS
- SCSS Modules

## Getting Started

1. **Install Dependencies**

```bash
# Backend
cd api-travel
npm install

# Frontend
cd ../travel
npm install
```

2. **Environment Setup**

Create `.env` file in `api-travel` directory with:
```
MONGO_URL=your_mongodb_url
JWT_SECRET=your_jwt_secret
```

3. **Run the Application**

```bash
# Start Backend
cd api-travel
npm start

# Start Frontend
cd travel
npm start
```

## Features
- User authentication and authorization
- Place listing and management
- Booking functionality
- Image upload for places
- Responsive design
- User profile management

## File Structure
```
api-travel/           # Backend
├── models/          # Database models
├── uploads/         # Uploaded files
└── index.js         # Main server file

travel/              # Frontend
├── public/
├── src/
│   ├── Components/
│   └── ...
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
