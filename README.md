# Angular Assigment


### NOTE: You must have git and node installed !
---------

#### How to get started:
----
Clone this repository

Install packages using `npm install`

Start the application using `npm start`

Start the REST api server using `npm run json-server` (will be served on `http://localhost:3000`)


#### flights REST api details

The application uses `json-server` to create an API that you can then get data from.

For example: http `GET` request to `http://localhost:3000/flights` will return all flights.


#### Available api routes:

`GET /flights` return all flights
  
`GET /flights/1` return flight with id 1
  
`PUT /flights/1` save flight with id 1
  
`GET /pilots` return all pilots


#### Application requirements:

* home page to display all flights (display only number and route)
  - user should be able to click on a flight and navigate to the details page

* details page to display flight data
  - allow the user to change the check-in status.
  - display dropdown to select a pilot
  - allow the user to save his changes

* use components to re-use functionality


#### Bonus

* implement search field on the home page
