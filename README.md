# Prebuilt Checkout page with subscriptions

Explore a full, working code sample of an integration with Stripe Checkout and Customer Portal. The client- and server-side code redirects to a prebuilt payment page hosted on Stripe. Included are some basic build and run scripts you can use to start up the application.

## Running the sample

1. Build the server

```
npm install
```

2. Run the server

```
npm start
```

3. Create your `/webhook` endpoint and get your webhook secret key in the [Dashboard](https://dashboard.stripe.com/test/webhooks). Use this to replace the whsec_12345 in the Server file.

4. Go to [http://localhost:4242/](http://localhost:4242/)
