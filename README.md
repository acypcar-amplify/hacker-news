# Hacker News: a GraphQL server using Node.js, the graphql-yoga server library and Prisma

## Install dependencies
    npm install

## Deploy prisma
    cd database
    prisma playground

## Run the server
    node src/index.js

## Get a token
    cd database
    prisma token

## Add the token to the HTTP HEADERS
    {
       "Authorization": "Bearer <token>"
    }

## Start executing mutations, queries and subscriptions!
