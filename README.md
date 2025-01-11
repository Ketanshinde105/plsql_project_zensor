# Pet House Management System

# Created By   : Ketan Shinde
# Collage Name : Amrutvahini Collage Of Engineering,Sangamner



## Description:
    The Pet House Management System is a software solution designed to help pet care businesses (e.g., pet hotels, grooming centers, shelters) 
    efficiently manage their operations. It allows businesses to handle pet and owner details, schedule services (boarding, grooming, etc.), track payments, and maintain health records.

## Key Features:
1.Owners Table:
     Stores owner details with unique owner_id.
     Includes email (unique), phone, and registration_date (default: current date).

2.Pets Table:
     Manages pet details with unique pet_id.
     Links each pet to an owner via owner_id (foreign key).
     Tracks admission date (default: current date).

3.Veterinarians Table:
     Holds veterinarian information with unique vet_id.
     Includes specialization and contact details.

4.Pet Care Table:
     Tracks pet care activities with unique care_id.
     Associates activities (e.g., grooming, feeding) with pets using pet_id (foreign key).

5.Appointments Table:
    Manages appointments with unique appointment_id.
    Links pets and vets via pet_id and vet_id (foreign keys).
    Includes status (Scheduled, Completed, Cancelled).


## Benefits:
Streamlines pet care operations.
Improves customer experience with easy bookings and payment tracking.
Manages pets’ health and service history effectively.
The system aims to optimize business processes, improve operational efficiency, and enhance customer satisfaction in pet care services.

# Gauidance:=Aniruddha Gaikwad.


  
