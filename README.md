## About
The app was created using [strapi-docker](https://github.com/strapi/strapi-docker), if something breaks, blame them.

## How to run
Go to root, then: 
```
docker-compose up
```

## Other
Changes to the database structure are reflected in the `api` directory, just
commit those.
Strapi does not currently support data migrations or seeding.
