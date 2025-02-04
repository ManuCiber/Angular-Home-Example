## App Tutorial

Welcome to the *Tutorial App*...
This app was made with Angular framework. This tutorial was based at the Angular's example.

## Characteristics

* Layout Design
* Card example
* Use Https request (Fetch)

## Requirements

To run or use this repository, you need:

* NodeJS (v.17 or better)
* Git and Github
* A little time
* npm gestor

## Steps to run 

1. Copy, clone or donwload this repository in your desktop (Also you can use Github Desktop).

```bash
git clone https://github.com/ManuCiber/Angular-Home-Example
```

2. Change to the carpet if is neccesary:

```bash
cd Angular-Home-Tutorial
```

3. Install the modules neccesary to run:

```bash
npm install
```

```bash
npm -g install json-server
```


4. Run the json server before run the application:

```bash
json-server --watch db.json
```
This will Open a Window to show the data content in the file:
For example: 

```json
{
    "id": "0",
    "name": "Acme Fresh Start Housing",
    "city": "Chicago",
    "state": "IL",
    "photo": "https://angular.dev/assets/images/tutorials/common/bernard-hermant-CLKGGwIBTaY-unsplash.jpg",
    "availableUnits": 4,
    "wifi": true,
    "laundry": true
  }
```

Note: This file will watch in http://localhost:3000/
Endpoints: http://localhost:3000/locations

5. Run this application:
```bash
ng serve
```

## Tecnologies Used

- *Angular*: Framework Principal Web
- *Json*: ORM to the database
- *HTML/CSS*: Design and Styles
- *TypeScript*: To the logic at this program

## Licence
This project is at License MIT. (This will be refreshed later)

## Author
- *Carlos Manuel* - [ManuCiber] (https://github.com/Manuciber)
