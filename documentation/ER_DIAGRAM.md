# ER Diagram
## Kotha Vellanti Water Management System

The database contains five main entities:

1. Admin
2. Residents
3. Complaints
4. Water Availability
5. Water Facilities

## Entity Relationships

- One resident can submit multiple complaints.
- An administrator manages water availability.
- An administrator manages water facilities.
- An administrator manages complaints.

## Database Entities

### Admin
- id (Primary Key)
- username
- password

### Residents
- id (Primary Key)
- full_name
- phone
- password

### Complaints
- id (Primary Key)
- resident_name
- phone
- area
- complaint_type
- description
- status

### Water Availability
- id (Primary Key)
- area
- supply_status
- supply_time
- remarks

### Water Facilities
- id (Primary Key)
- facility_name
- facility_type
- location
- status
- description
