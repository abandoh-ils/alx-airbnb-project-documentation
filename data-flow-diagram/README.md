# Data Flow Diagram (DFD) for AirBnB Clone System
This DFD visualizes how data moves between users, processes, and storage components in the Airbnb-like system. The flows highlight critical interactions like the booking/payment lifecycle and admin monitoring functions while maintaining clear separation between guest, host, and admin operations.

![L0-dfd-airbnb](/data-flow-diagram/data-flow.png)

*Level 0 Context diagram of AirBnB*

## DFD Components Explained:
1. **External Entities:**
    * **Guest:** Traveler searching/bookings stays
    * **Host:** Property owner managing listings
    * **Admin:** System administrator
    * **Payment Gateway:** External payment processor

2. **Key Processes:**
    * **Authentication:** JWT/OAuth login flows
    * **Property Management:** CRUD operations for listings
    * **Search & Filter:** Location/price/amenity queries
    * **Booking Engine:** Reservation and availability checks
    * **Payment Processing:** Transaction handling with gateways
    * **Review System:** Rating validation and responses
    * **Notification Service:** Event-based alerts
    * **Admin Dashboard:** Monitoring and moderation

3. **Data Stores:**
    * **Users DB:** Profiles and credentials
    * **Properties DB:** Listings and availability calendars
    * **Bookings DB:** Reservations and status history
    * **Payments DB:** Transactions and payout schedules
    * **Reviews DB:** Ratings and comments
    * **Messages DB:** Conversation history

![L1-dfd-airbnb](/data-flow-diagram/data-flow-diagram-L1.png)

*Level 1 Data flow diagram of AirBnB*



