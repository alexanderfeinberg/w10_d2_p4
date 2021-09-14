# Practice: Environment Variables

In this practice you will set up and work with environment variables in a
Node.js environment.

# Set up

`cd` into the `server` folder.

`npm install` the dependencies.

## Part 1: Command line

`index.js` contains a single `console.log` for the `NODE_ENV` environment
variable; however, it currently prints `undefined` when running:

```plaintext
> node index.js
> undefined
```

Run `index.js` again. This time with the `NODE_ENV` environment variable 
declared within the command line using the value "production".

## Part 2: Using `.env` file

`app.js` contains some boilerplate code for an Express server. However, it is
dependent on some environment variables located within `.env`. 

Create the __.env__ file with the appropriate environment variables. Then, use 
`dotenv` in __app.js__ to connect your environment variables so that the
application runs properly.

When connected properly, the server should:

- be listening on port 5000
- display the secret message "Hello from .env" at [http://localhost:5000]

[http://localhost:5000]: http://localhost:5000