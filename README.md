This is an assignment to find location analytics insights.

Dataset:

    id - booking ID

    user_id - the ID of the customer (based on mobile number)

    vehicle_model_id - vehicle model type.

    package_id - type of package (1=4hrs & 40kms, 2=8hrs & 80kms, 3=6hrs & 60kms, 4= 10hrs & 100kms, 5=5hrs & 50kms, 6=3hrs & 30kms, 7=12hrs & 120kms)

    travel_type_id - type of travel (1=long distance, 2= point to point, 3= hourly rental).

    from_area_id - unique identifier of area. Applicable only for point-to-point travel and packages

    to_area_id - unique identifier of area. Applicable only for point-to-point travel

    from_city_id - unique identifier of city

    to_city_id - unique identifier of the city (only for intercity)

    from_date - timestamp of the requested trip start

    to_date - timestamp of the trip end

    online_booking - if the booking was done on the desktop website

    mobile_site_booking - if the booking was done on mobile website

    booking_created - time stamp of booking

    from_lat - latitude of from area

    from_long -  longitude of from  area

    to_lat - latitude of to area

    to_long - longitude of to area

    car_cancellation - whether the booking was canceled (1) or not (0) due to the unavailability of a car.
