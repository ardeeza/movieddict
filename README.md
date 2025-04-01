# Movieddict

Movieddict- An online search tool that allows all movie buffs out there to browse through a list of publicly released Hollywood movies. Tired of constantly searching for that beloved movie? Rest assured - the "favourite button" feature allows you to view all "favourited" movies in a single space.

[image](https://github.com/user-attachments/assets/876f26f7-eb04-4069-a874-b281542019a0)

[image](https://github.com/user-attachments/assets/f1a8bcd4-adc9-43ca-b498-98a938ef651c)


## Getting Started!


1. Head over to the [TMDB](https://www.themoviedb.org/) page and create an account for an API key.
2. Install all the dependencies listed in package.json in your React project.
3. Substitute your API ID and Key in the following URL in api.js located in  > services folder
   >

     const response = await fetch(`${BASE_URL}/movie/popular?api_key=${API_KEY}`);
## Upcoming Features
1. Users will be alllowed to create personal accounts which facilitates access of "Favourite movies" list on multiple devices.
2. Addition of a "Genre" tab which will allow users to search for all relevant films grouped under a specific genre.
