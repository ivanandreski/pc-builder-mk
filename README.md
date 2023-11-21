# PC Builder MK

PC Builder MK is a site which takes inspiration from the already existing [a link](https://pcpartpicker.com/). The project gathers information from macedonian computer stores about the products they sell, their prices and all available information using web scraping. The information is then stored in a database, where it is served to a client side application using an api. The project also allows users to choose from all the available products and check information about them in one place. Also they can choose the products for a new computer build and check wether they are compatible with eachother. The project also has a simple forum implementation where users can ask and answer questions from other users. The forum is a simple copy of reddit where users can upvote or downvote comments so each user has some kind of a score on the forum.

# Usage
This repository is used to hold scripts that clone all the necesary modules
in one folder from different repositories. The scripts are used to automate the process.
The docker-compose file is used to start the project in one command.

# Repositories
Each repository has their own readme file which explains their usage
## Web Scraper
[a link](https://github.com/ivanandreski/pc-builder-mk-scraper)

## Api
[a link](https://github.com/ivanandreski/pc-builder-mk-api)

## Client app
[a link](https://github.com/ivanandreski/pc-builder-mk-web)

## Old client app
This project first started with a flutter mobile app, but the app has not been updated in a long time and the api responses might not be the same.
[a link](https://github.com/ivanandreski/pc-builder-mk-mobile)
