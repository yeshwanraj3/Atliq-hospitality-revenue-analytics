Metrics Design Strategy I used:

All KPIs in this project are implemented using DAX measures
to ensure:
- Reusability across visuals
- Consistent business logic
- Clean separation of data and calculations

Metric definitions are standardized using a centralized
metrics reference file.

1)Total Revenue =
SUM(fact_bookings[revenue])
2)Total Bookings =
COUNT(fact_bookings[booking_id])

3)Occupancy % = DIVIDE(
    [Total Bookings],
    [Total Available Rooms])

Measures room utilization efficiency.    

4)ADR = DIVIDE(
    [Total Revenue],
    [Total Bookings])
    
Avg daily rate : Average revenue earned per occupied room.

5)RevPAR = [ADR] * [Occupancy %]
Overall hotel performance metric combining pricing and occupancy.

other metrics like DSRN DURN are in an csv file contaning all metrics used in the project....
