# Freetan
An open-source, TypeScript based implementation of Settlers of Catan

Freetan is a lightweight, browser based implementation of the Settlers of Catan game. Existing web options are ludicrously expensive. I'd like to change that.

Freetan is currently a headless TypeScript based game engine only. The plan is to plug it in to a React front-end but it also may make more sense to just go with a JS.canvas based front-end given that the game-engine is designed around cube coordinates which should lend itself to easy canvas drawing implementations. 

Networking concerns are also TODO. A webapp GUI wrapper around the base game with a lobby would also be nice long term. And some persistent storage for user configurations within browser would be nice as well. Perhaps Redis or something NoSql-y
