# Django API Overview  

# Database Modeling and Data Seeding in Django

##  Objective  
Define database models, create serializers for API data representation, and implement a management command to seed the database.

## 🔹 Duplicate Project  
The original project `alx_travel_app` was duplicated into `alx_travel_app_0x00` for implementing data modeling and seeding.

##  Models  
Defines database structure in `listings/models.py`:  
- **Listing**: Stores travel accommodations.  
- **Booking**: Manages reservations & statuses.  
- **Review**: Captures user ratings & feedback.  

##  Serializers  
Converts models into JSON in `listings/serializers.py`:  
- **ListingSerializer** → Formats listing data.  
- **BookingSerializer** → Handles bookings.  

##   Data Seeding (`listings/management/commands/seed.py`)  
  
 Data Seeding (`listings/management/commands/seed.py`)  
  
Run the command:  
```bash
python manage.py seed
