FORMAT: 1A

# [UNMAINTAINED] FeedHenry Stripe Connector
[![Dependency Status](https://img.shields.io/david/feedhenry-templates/fh-connector-stripe-cloud.svg?style=flat-square)](https://david-dm.org/feedhenry-templates/fh-connector-stripe-cloud)

The FeedHenry Stripe Connector. For more information on Stripe see: [https://github.com/stripe/stripe-node](https://github.com/stripe/stripe-node).

# Group Stripe Connector API

# Stripe [/cloud/stripe]

Add customer

## Stripe [POST] 

Authenticates with Stripe and adds a customer

+ Request (application/json)
    + Body
        {
          "email": "customeremail@example.com"
        }

+ Response 200 (application/json)
    + Body
            {
              "ok": "true"
            }
