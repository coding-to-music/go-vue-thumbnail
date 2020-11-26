# Website Thumbnail Generator

Generate a thumbnail of any website.
Written in Go and Vue. 
Original Source Code [here](https://github.com/Dirk94/website-thumbnail-generator)
How to Set Up a Real-World Project with Go and Vue
by Dirk Hoekstra
Tutorial Article [here](https://www.freecodecamp.org/news/how-i-set-up-a-real-world-project-with-go-and-vue/)

This project uses [screenshotapi.net](https://screenshotapi.net) head over there to create an account and get an API token.

[View the live version here!](https://coffeecoding.dev/website-thumbnail-generator)

## Go server

*Replace the `SCREENSHOTAPI_TOKEN` with your screenshotapi.net token.*

To run the go server run the following command from the project root directory.

I need to separate main.go from server.go

for servers 

```
go run main/server.go
```

## Frontend

Navigate to the `frontend` directory and run the following command to install required packages.
```
yarn install 
```

To start up the frontend development server run:
```
yarn serve
```

To build the frontend for production use run:
```
yarn build
```