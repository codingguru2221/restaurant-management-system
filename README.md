# Hotel Management System

## Overview
The **Hotel Management System** is a Python-based application that facilitates seamless management of hotel operations. It provides functionality for:

- **User Management**: Separate roles for Admin, Staff, and Customers.
- **Room Booking**: A user-friendly interface to view room details and make bookings.
- **Food Ordering**: A menu-driven system to order a variety of cuisines.
- **Event Management**: Organize and book events like weddings, conferences, and parties.

This system ensures efficient hotel operations while enhancing the guest experience.

---

## Features

### 1. User Roles
- **Admin**:
  - View all users (Admins, Staff, and Customers).
  - Promote users to Admin role.
  - Delete users and manage staff positions.
- **Staff**:
  - Perform hotel operations based on their role (e.g., chef, receptionist, etc.).
- **Customer**:
  - Book rooms, order food, and organize events.

### 2. Room Management
- Display available rooms with detailed information:
  - **Room Types**: Tower Exclusive, ITC ONE, Luxury Suite, ITC Royal, etc.
  - **Pricing**: Detailed price range for each room type.
  - **Amenities**: Complimentary Wi-Fi, flat-screen TVs, minibar, room service, etc.
- Simple and efficient room booking system.

### 3. Food Ordering System
- Categorized menu:
  - Drinks: Soft drinks, juices, tea, and coffee.
  - Vegetarian food: Biryani, Paneer dishes, and more.
  - Non-vegetarian food: Fish curry, Chicken Tikka, etc.
  - Chinese food: Manchurian, Chowmein, Fried Rice.
- **Discounts and Offers**:
  - 10% off on orders above ₹1000.
  - Special discounts for birthday parties.

### 4. Event Management
- Event Types:
  - Birthday parties
  - Wedding events
  - Anniversaries
  - Holiday parties (e.g., Christmas, New Year)
  - Conferences
- Pricing models:
  - Per-person pricing
  - Package deals
- Customizable facilities like catering, photography, entertainment, and decorations.

---

## Installation and Setup

### Prerequisites
- Python 3.x installed on your system.
- Basic knowledge of running Python scripts.

### Steps to Run
1. Clone this repository or download the source code.
2. Navigate to the project directory.
3. Ensure the `data` folder exists with proper file permissions.
4. Run the main script:
   ```bash
   python main.py
   ```
5. Follow the on-screen instructions to use the application.

---

## File Structure
```
HotelManagementSystem/
├── data/
│   ├── admins.txt       # Stores admin user data.
│   ├── staff.txt        # Stores staff user data.
│   ├── users.txt        # Stores customer user data.
│   ├── bookings.txt     # Stores room booking details.
│   ├── food.txt         # Stores food order details.
├── main.py              # Entry point of the application.
├── README.md            # Project documentation.
└── ...                  # Additional Python files and resources.
```

---

## Future Enhancements
- **Online Payment Integration**: Add support for secure payment options.
- **Real-time Notifications**: Send SMS or email confirmations for bookings and orders.
- **Advanced Analytics**: Generate reports on room bookings, food orders, and events.
- **Multilingual Support**: Make the application accessible to users in multiple languages.

---

## Contributions
Contributions are welcome! Feel free to open issues or submit pull requests for new features, bug fixes, or documentation improvements.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact
For inquiries, suggestions, or support, contact:
- **Email**: support@hotelmanagement.com
- **GitHub**: [Your GitHub Profile](https://github.com/codingguru2221)

## Made BY The Codex And Team..

