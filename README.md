# Resy

## scrape_info

This scrapes all restaurants in NYC on Resy for:

- Cuisine
- Stars
- Count
- Neighborhood
- Available
- Sold-out

 "Available" gives how many days a restaurant has in the future with at least one available slot, and "Sold-out" gives how many days with no available slots. Results can be sorted to show which restaurants are hardest to book. Example output:

<img width="1235" alt="Screenshot 2023-05-01 at 10 43 24 PM" src="https://user-images.githubusercontent.com/67289464/235568798-c8080663-c675-4c35-9ae6-73384701355e.png">

## scrape_availabile

This continuously scrapes a given list of restaurants to find open slots, then sends an email when it finds one. It is similar to the "Notify me" button on Resy, but it runs every minute over multiple restaurants for all future days. It is also more customizable, for example you can limit it to meals between 5pm and 9pm.

<img width="858" alt="Screenshot 2023-05-01 at 11 01 19 PM" src="https://user-images.githubusercontent.com/67289464/235570848-e83b923e-8312-4e02-bec1-98bfb8f9eba0.png">
