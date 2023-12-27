# API_Testing_Restful-Booker
## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run API_Testing2.postman_collection.json -e API_Testing2.postman_environment.json
```
- Run Command for Report: 
```console 
newman run API_Testing2.postman_collection.json -e API_Testing2.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- file:///D:/All%20course/SQA%20Course/API%20testing/API%20Testing.pdf

## Test case list:
1. ### Create Booking
      > Create Data Sets Using the Dynamic Random Variables.

2. ### Get Booking
      > Get the data sets after completing the create booking
      1. > First Name
      2. > Last Name
      3. > Totalprice
      4. > Depositpaid
      5. > Checkin
      6. > Checkout
     
3. ### Create Token
      > Create token and add the token id in environment
 
4. ### Update Booking
      > Update Data Sets Using the Dynamic Random Variables.
	
5. ### Get Update Booking
      > Get the data sets after completing the uodate booking
      1. > First Name
      2. > Last Name
      3. > Totalprice
      4. > Depositpaid
      5. > Checkin
      6. > Checkout

6. ### Delete Booking
      > In the test case you need to validate the following field values:
      1. > Only Message

## Newman Report Summary:
![Newman Report Summary](https://github.com/fairuzzahin/API_Testing_TestingWorld/assets/87386589/5a0aa378-db5f-4549-ab34-a8808eb7c20e.png)

![Newman Report Summary](https://github.com/fairuzzahin/API_Testing_TestingWorld/assets/87386589/94d7f25e-97ff-4867-909d-f16ae317dd45.png)
