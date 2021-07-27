# Essence & Elements - Backend

![Essence & Elements Banner Image](public/img/banner.webp)

This repo contains the backend CMS intended to interact with the frontend website for _Essence & Elements_: a company specialising in selling natural healing products and services. Developed primarily with Strapi, GraphQL and PostgreSQL.

For more detailed information on the project, please see the [Frontend Repo](https://github.com/vitamins999/essence-and-elements).

## Technology Used

- Strapi
- GraphQL
- PostgreSQL

## Run Locally

Clone the project

```bash
  git clone https://github.com/vitamins999/essence-and-elements-backend.git
```

Go to the project directory

```bash
  cd essence-and-elements-backend
```

Install dependencies

```bash
  npm install
```

Set up database and environment variables (see below)

Start the server

```bash
  npm run develop
```

## Environment Variables

To run this project, you will need to set up a postgreSQL database either locally or remote, and add the following environment variables to your .env file

`DATABASE_NAME` - The name of the database. Usually defaults to **postgres**.

`DATABASE_USERNAME` - The username used to log into the database. Usually defaults to **postgres**.

`DATABASE_PASSWORD` - The user's password to log into the database.

`DATABASE_HOST` - The connection url for the database.

`ADMIN_JWT_SECRET` - The JWT secret you want to use for admin accounts when logging in. Can be anything, just make sure it's not made public.

## Authors

- [Jools Barnett](https://www.github.com/vitamins999)
