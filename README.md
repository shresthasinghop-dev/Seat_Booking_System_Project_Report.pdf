# Seat Booking System

## About the Project

This is a Python-based seat booking system made for the VITyarthi project.

The basic idea is simple: instead of keeping track of seats manually, the
user can open the program and use a menu to see the seats, book a seat,
cancel a booking, search for a booking, or see all current bookings.

I kept it as a console program because the Python logic is easier to see,
understand and explain.

## Features

- 5 × 6 seat layout
- Seat availability display
- Booking a free seat
- Duplicate booking prevention
- Automatic booking ID
- JSON data storage
- Booking cancellation
- Booking search
- View all bookings
- Basic input validation
- Automated tests

## Technologies

- Python 3
- JSON
- dataclasses
- datetime
- pathlib
- unittest
- Git / GitHub

No third-party Python packages are required.

## Run the Program

```bash
python src/seat_booking.py
```

## Run the Tests

```bash
python -m unittest discover -s tests -v
```

## Project Structure

```text
Seat_Booking_System/
├── src/
│   ├── __init__.py
│   └── seat_booking.py
├── tests/
│   └── test_seat_booking.py
├── data/
│   └── bookings.json
├── docs/
├── screenshots/
├── statement.md
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

## Future Improvements

The project could later be extended with multiple shows, different seat
categories, a GUI, a database, login accounts and online booking.

The current version is intentionally kept at a student-project level so the
logic is clear rather than hidden behind a large framework.
