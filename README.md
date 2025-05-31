# Django API Overview  

## 📌 Models  
Defines database structure in `listings/models.py`:  
- **Listing**: Stores travel accommodations.  
- **Booking**: Manages reservations & statuses.  
- **Review**: Captures user ratings & feedback.  

## 📌 Serializers  
Converts models into JSON in `listings/serializers.py`:  
- **ListingSerializer** → Formats listing data.  
- **BookingSerializer** → Handles bookings.  

## 📌 Data Seeding  
Seeds database with sample listings in `listings/management/commands/seed.py`.  
Run the command:  
```bash
python manage.py seed