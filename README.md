# My Shop

Project developed using React and TypeScript, the application consumes the Stripe API simulating a purchase in an online t-shirt store. The objective of the project is to create an ecosystem that consumes a robust ready-made API, having a success screen with API callback.

## The idea

The project simulates a virtual store, the products displayed in the carousel are registered and are searched through the Stripe API. The application uses Next's SSG (Static Site Generation) technique on pages that can be generated statically. When starting a checkout, the application starts a checkout session on Stripe, after the test data is filled in, the user is redirected to a success page with the data filled in on Stripe.

## Deploy

You can check out the project live by [clicking here](https://my-shop-one-bice.vercel.app/).

## Used tools:
- React
- Typescript
- Next
- Stitches
- Stripe API
- Axios
- and others

## Screenshots

### Homepage screen
![Homepage](/src/assets/homepage.png?raw=true "Homepage")

### Single product page
![Homepage](/src/assets/product-page.png?raw=true "Single product")

### Stripe checkout
![Homepage](/src/assets/stripe-checkout.png?raw=true "Stripe checkout")

### Success page
![Homepage](/src/assets/success-page.png?raw=true "Success page")
