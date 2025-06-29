# AirBnB Clone Use Cases
This diagram visualizes all core interactions in the Airbnb-like system, showing how different user roles interact with the platform's key features. The «include» and «extend» relationships highlight critical workflow dependencies between use cases.

## Key Interactions:
1. **Guest Interactions:**
    * Search → Book → Payment workflow
    * Write reviews after completed bookings («extend»)
    * Messaging with hosts

2. **Host Interactions:**
    * Create listings → Manage availability
    * Respond to guest reviews
    * Communicate with guests

3. **Admin Interactions:**
    * User management
    * Listing verification
    * Financial reporting

4. **Shared Functionality:**
    * Registration/login for all users
    * Messaging system between guests/hosts
    * Dependency relationships:
        * Booking «include» Payment
        * Review «extend» Booking

## Styling Notes:
1. **Actors:** Stick figures on left side
2. **System Boundary:** Large rectangle containing use cases
3. **Use Cases:** Ellipses with descriptive labels
4. **Relationships:**
    * Solid lines: Actor → Use Case
    * Dashed arrows: «include» and «extend» dependencies
5. **Text Labels:** Dependency types clearly marked

## Visual Layout

![UD-airbnb](/use-case-diagram/UD-airbnb.png)

*Use case diagram for the AirBnB clone*
