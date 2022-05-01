# API League Of Legends
1. API that consumes some official riot games API's related to league of legends and assembles a unique return to be consumed by another front-end application

# Technology
1. NodeJs

# How to use:
1. clone the project
2. use npm install to install the dependencies
3. use cp .env.example .env to copy the environment variables
4. npm run dev-start to start the application
5. make a request in postman or insomnia: http://localhost:3001/summoner/summoner-name
    5.1 E.g: http://localhost:3001/summoner/Lukitão

# Official API Riot Games:
1. to get the credentials to use the official riot api go to: https://developer.riotgames.com/ and create your account

# Dependencies used in the application
1. axios: make requests to API's
2. cors: accept requests from the front application
3. express: server
4. dotenv (dev): use and save .env environment variables in the application
5. nodemon (dev): keep the server updating every update during development

# API return example
```
{
    "summonerLevel": 493,
    "tier": "PLATINUM",
    "rank": "IV",
    "wins": 40,
    "losses": 39,
    "queueType": "RANKED_SOLO_5x5",
    "iconUrl": "https://ddragon.leagueoflegends.com/cdn/12.8.1/img/profileicon/582.png",
    "winRate": "50.63"
}
```

# Next steps
1. add docker
