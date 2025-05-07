# Backend Requirement Specifications

## 1. User Authentication
- POST /api/register
- POST /api/login
- JWT authentication with role-based access
- Password hashing, input validation

## 2. Property Management
- GET /api/properties
- POST /api/properties
- PUT /api/properties/:id
- DELETE /api/properties/:id
- Host-only access, image upload support

## 3. Booking System
- POST /api/bookings
- GET /api/bookings/user
- Date validation, overlap check
- Real-time availability check
