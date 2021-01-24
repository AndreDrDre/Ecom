# Ecom

An ecommerce store developed using the Django framework. The site is hosted on heroku and provides the ability for both authenticated and authenticated users to purchase products. Paypal integration is present for display purposes but not activated.

## Functionallity

- Guest Shopping
- Authenicated User shopping
- Update cart/(change quanitity & delete item)
- Cart status saved
- Payment integration. ( disabled, only visible for visual affects)

## Deployment 

- Deploy your git repository via the the heroku CLI. Here is a link : https://devcenter.heroku.com/articles/git

## Suggestions

- I am currently having issues with loading my static files directly on heroku dude to pipeline configuration( when Heroku decides to load what).
- I am going to load my files to aws and call them from there. Expect this update shortly.
- Integration with PostgreSQL seems to be straight forward with Heroku and thus i will be moving my local data into PostgresQL.
