## Project Introduction

This Project implements a Restaurant Ordering System supported by backend in NodeJS (Express Server and EJS templating), frontend built and styled using SASS pre-processor, HTML5 & JQuery, and PostreSQL for database storage and operations. Realtime order updates are sent to both owner of the restaurant and the customer using Twilio SMS API whenever order is place, confirmed and ready for pickup.

## Illustration

Below are some of the routes a user can visit.
!['Home Page'](https://github.com/aaron3993/Aa-So-Sa/blob/master/documentation/home.png)
!['Menu Page'](https://github.com/aaron3993/Aa-So-Sa/blob/master/documentation/menu.png)
!['Order Page'](https://github.com/aaron3993/Aa-So-Sa/blob/master/documentation/new_order.png)
!['Completed Order Page'](https://github.com/aaron3993/Aa-So-Sa/blob/master/documentation/completed_order.png)
!['Admin Page'](https://github.com/aaron3993/Aa-So-Sa/blob/master/documentation/admin.png)

## Planning

!['Entity Relation Diagram'](https://raw.githubusercontent.com/aaron3993/midterm-project/master/documentation/Database%20ERD.png)
Fig 1. Entity Relation Diagram

!['RESTful routes'](https://raw.githubusercontent.com/aaron3993/midterm-project/master/documentation/RESTful%20Route%20Panning.png)
Fig 2. RESTful routes planning

!['Wireframe1'](https://raw.githubusercontent.com/aaron3993/midterm-project/master/documentation/wireframe1.png)
Fig 3. Mockups & Wireframe 1

!['Wireframe2'](https://raw.githubusercontent.com/aaron3993/midterm-project/master/documentation/wireframe2.png)
Fig 4. Mockups & Wireframe 2

## User Stories

- Users can see the list of available dishes (menu)
- Users can add dishes to the cart
- Users can see the content of their cart and the details about the dishes, and the order total
- Restaurant owner will receive an SMS notification that an order was made with the order details
- Users will receive a notification that their order is ready
- Users can modify the content of the cart
- Users can place their order
- Users will receive a notification about when their order will be ready
- Users should see the status of their order on the app (approx. time for pickup)
- Restaurant owner can specify how long the order will take to be fulfilled

## Dependencies

1. express
2. bodyParser
3. sass
4. morgan
5. cookieSession
6. node-postgresql
