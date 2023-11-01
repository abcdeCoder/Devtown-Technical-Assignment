In this project **Devtown Technical Assignment**, I  build a **product list** app by using React



### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>

<details>

<summary>API Requests & Responses</summary>
<br/>

**productsApiUrl**

#### API: `https://apis.ccbp.in/products`

#### Example: `https://apis.ccbp.in/products?sort_by=PRICE_HIGH&category=4&title_search=machine&rating=4`

#### Method: `GET`

#### Description:

Returns a response containing the list of Products

#### Success Response

```json
{
  "products": [
    {
      "title": "Front Load Machine",
      "brand": "Samsung",
      "price": 22490,
      "id": 24,
      "image_url": "https://assets.ccbp.in/frontend/react-js/ecommerce/appliances-washing-machine.png",
      "rating": 4.5,
    },
      ....
  ]
}
```

</details>



<details>
<summary>Implementation Files</summary>
<br/>

Use these files to complete the implementation:

- `src/components/AllProductsSection/index.js`
- `src/components/AllProductsSection/index.css`
- `src/components/FiltersGroup/index.js`
- `src/components/FiltersGroup/index.css`
</details>

### Important Note


<summary>Click to view</summary>

<br/>

**The following instructions are required for the tests to pass**

- `Home` Route should consist of `/` in the URL path
- `Login` Route should consist of `/login` in the URL path
- `Products` Route should consist of `/products` in the URL path
- `Cart` Route should consist of `/cart` in the URL path
- No need to use the `BrowserRouter` in `App.js` as we have already included in `index.js`

- User credentials

  ```text
   username: raja
   password: raja@2021
  ```

- The rating stars images in the route should have the alt attribute value as **rating {ratingId}**


