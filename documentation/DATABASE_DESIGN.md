# Database Design

## Database Name
water_management

## Tables

### 1. Admin
Stores administrator login details.
- id
- username
- password

### 2. Residents
Stores registered resident details.
- id
- full_name
- phone
- password
- created_at

### 3. Complaints
Stores water-related complaints submitted by residents.
- id
- resident_name
- phone
- area
- complaint_type
- description
- status
- created_at

### 4. Water Availability
Stores water supply information.
- id
- area
- supply_status
- supply_time
- remarks
- updated_at

### 5. Water Facilities
Stores information about water facilities.
- id
- facility_name
- facility_type
- location
- status
- description
- created_at

## Database Technology
MySQL / MariaDB

## Database Purpose
The database stores administrator details, resident details, complaints, water availability and water facility information.
