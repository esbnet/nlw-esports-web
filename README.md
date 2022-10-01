# nlw-esports-web

Is a web aplication to consumers API [nlw-esports-web](https://github.com/esbnet/nlw-esports-server)

## Pré-requisites

- node
- server running ([how to isntall and run](https://github.com/esbnet/nlw-esports-server))

## Technologies:

- react
- axios
- tailwindcss
- typescript

## How it works:

1. Select the game:
   ![Main Page](.\src\assets\img\Main.png)
2. Fill the form for include yours your availability to play it:
   ![Create Ad Page](src\assets\img\CreateAd.png)

## Installation

Clone this project into your project directory:

`git clone https://github.com/esbnet/nlw-esports-web.git`

## Start

Run the following command to start the aplication:

`yarn install && yarn dev`

## End-Points:

The application consumes the following end-points:

- GET `/games'` - Get a list of games
- POST `/game/:id/ads` - Create a ad for the game by id
- GET `/games/:id/ads` - Get ad for the game by id
- GET `/ads/:id/discord` - Get ads for the game selected
