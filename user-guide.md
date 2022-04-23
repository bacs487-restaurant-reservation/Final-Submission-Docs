# User guide for Restaurant App
- If you are viewing the restaurants and you would like to choose "make a reservation" at one of them, you can click on the "Select Table" button underneath the restaurant card itself.
- If you are viewing the restaurants but want to narrow down your choices you may enter a zip-code in the search bar at the top of the screen and see which restaurants are located in that area.
- Once you have selected a restaurant and are viewing the seating chart of the restaurant, you may select whichever table you like. Each restaurant has a variety of tables that you can choose from. 
- Once you have selected a table of your choice, by pressing the "SELECT" button, a random code will appear that you can show to the host once you have arrived at the restaurant. 

## Installing the frontend locally

- Copy the frontend repository:
```
git clone https://github.com/bacs487-restaurant-reservation/restaurant-frontend-doug.git
```

- cd into the working directory and then the src directory

```cd restaurant-frontend-doug/src```

- Install the required NPM packages:

``` npm install ```

- Run the frontend:
``` npm start ```

A window should open in your default browser with the frontend loaded up. If it does not, navigate to localhost:3000 in your browser.

You will  notice that the default frontend is connect to local json data rather than the database. This is for security purposes as our PostgreSQL database is restricted to incomming connections and requests from our server only. This sample data will allow you to observe the functionality of the frontend.

Search examples
- 80524
