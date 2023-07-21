# Hyperswitch HTML + Go Integration

Build a simple checkout form to collect payment details. Included are some basic
build and run scripts you can use to start up the application.

## Running the sample

1. Add your keys :
    - Navigate to `public/script.js` and replace the placeholder `HYPERSWITCH_PUBLISHABLE_KEY` with your publishable key.
    - Navigate to `server.go` and replace the placeholder `HYPERSWITCH_API_KEY` with your API key.

2. Run the server :
~~~
go run server.go
~~~

3. The sample app is now accessible here : [http://localhost:4242/index.html](http://localhost:4242/index.html).
