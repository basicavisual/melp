# melp

> My philosophy is that design must follow function, function must follow technology (tech in the ample sense), technology must follow the process, and process follows the problem. And if possible, the problem follows the root of the problem. Each product, therefore, must begin with the analysis of the problem.

Melp is a concept app that was requested as a test. I will describe the process for the concept within these documents.

The initial request was this:

> Melp is a business focused on showing information about the best restaurants in the
city. They have a pretty successful mobile application and are planning to expand
their market through a web platform.

The data provided has this structure:
```
}
    "id": "3765054a-c706-4dcd-8424-aa8db4e5a4bd",
    "rating": 4,
    "name": "Casárez S.L.",
    "contact": {
      "site": "https://julio césar.gob.mx",
      "email": "Isaac86@gmail.com",
      "phone": "567057696"
    },
    "address": {
      "street": "808 Noriega Pasaje",
      "city": "La Paz Lucasbury",
      "state": "Jalisco",
      "location": {
        "lat": 19.435477296009665,
        "lng": -99.1257455545481
      }
    }
  }
  ```

The requirement was to make the data shine. However the dataset fields are scarce for much functionality. So a proposal needed to be made with this requirement.

## The concept

Given the small amount of data columns available, I'm proposing to add value to the data through filtering. Filtered and curated data adds value to the dataset, so the concept proposal is for the top 5 restaurants in each state. The user will be able to query by state and get the following functionality:
- Visit the restaurant site
- Make a reservation
- Find out how to get there

The idea is that if the user wants to try the best, and only the fest of the food in town, they use melp to get a curated culinary tour. This is **the problem** melp app is trying to solve.

## The design

## The interface

## The technology
