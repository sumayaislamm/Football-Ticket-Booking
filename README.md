# Football Ticket Booking System

## Project Overview
This project is a database design for a Football Ticket Booking System. It manages users, football matches, and ticket bookings using PostgreSQL.

## Database Tables

### Users
- user_id (PK)
- full_name
- email
- role
- phone_number

### Matches
- match_id (PK)
- fixture
- tournament_category
- base_ticket_price
- match_status

### Bookings
- booking_id (PK)
- user_id (FK)
- match_id (FK)
- seat_number
- payment_status
- total_cost

## Relationships
- One User → Many Bookings
- One Match → Many Bookings
- Each Booking belongs to one User and one Match

## Files
- `schema.sql` → Database schema, constraints, and sample data
- `QUERY.sql` → SQL queries for the assignment

## Tools Used
- PostgreSQL
- Beekeeper Studio
- Draw.io

## ERD
ERD Link: [ (https://drive.google.com/drive/folders/1qSWEjS7a73Xk3PqNBi3ge6k021MCu3F1?usp=sharing) ]

## Author
Sumaya Islam