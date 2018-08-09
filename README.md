# NOTIFICATIONS

ETA notifications implementation with Node.js/Express and Twilio.

## Run the application

1. Install MongoDB


2. Clone the repository and `cd` into it.


3. Install the application dependencies


4. Copy the sample configuration file and edit it to match your configuration.Remember to set your MongoDB connection strings for both environments.


5. Seed the initial data into the database

   ```bash
   $ mongo localhost/eta-notifications-node seed/orders.js
   ```

6. Start the development server

    ```bash
    $ npm start
    ```

7. Expose the application to the wider Internet. Use ngrok

    ```bash
    $ ngrok http 3000
    ```
