# Skedly v0.0.1
Open source reservation system (REST API web server) written in Go.

This is the 'basic' version of Skedly that uses SQLite as the data source.
The main purpose of this project is to create a simple-to-use booking/reservation system that anyone can download and configure as they see fit.

PostgreSQL will be supported at a later point, but now the focus is on actually making the software work out-of-the-box.

## ✨ What can Skedly actually do?
- Nothing to see here, yet.

## 📅 What's currently being worked on?
- Working on the basic API endpoints for now. See table.

### API Endpoints (Planned/Implemented)
| Route | Method | Payload | Results | Auth | Description | Implemented? |
|-----|------|------|-----|----|-----|-----|
| /api/bookings | GET | | Booking[] | Yes | Get all bookings | ❌
| /api/booking | POST | PartialBooking | Booking | Yes | Create new booking | ❌
| /api/users | GET | | User[] | Yes | Get all users | ❌
| /api/user | POST | PartialUser | User | Yes | Create new user | ❌
| /api/auth | POST | Credentials | JWT Token | No | Authentication/Authorization | ❌

This table is not yet complete, more endpoints will be listed soon. This is just a basic endpoints for now.