# Ticket distribution API

![Onebox logo](http://developer.oneboxtickets.com/img/Banner-Onebox-Rest-Api-3.png "Onebox API logo")

## API for authenticate on sale channels.
There are two API that a client must have to implement in order to perform a complete ticket booking flow in Onebox.

The first one is the **[Oauth2 Authentiation API](https://github.com/OneboxTM/oauth-api)**, this API will let you retrieve an authorization token to be used afterwards to call any service from the distribution API.

![Onebox Oauth2 flow](http://developer.oneboxtickets.com/img/OUTH2-API-diagram-flow.png "Onebox OAuth2 flow")

### 1. Authentication

1. OAUTH2 Bearer token

### 2. Basic booking flow

1. Download product catalogue
2. Availability (Widget or API)
3. Add seats to shopping cart
4. Create an order
5. *Process payment (client side)*
6. Confirm order
7. Download ticket

![Onebox logo](http://developer.oneboxtickets.com/img/APIFlow.png "API Flow")

**Notice** that you also will be able to search for events and activities, to manage promotions and to navigate across venues. Must see the distribution API online documentation: [Onebox Distribution API Documentation](http://developer.oneboxtickets.com)

---
