
## Run Development Server

First, install dependencies:

```bash
npm install
```

Then, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Run Production Server

You can run this project in production on a Linux machine with Node.js and NPM installed.


First, install dependencies:

```bash
npm install
```

Then, create a production build:

```bash
npm run build
```

Finally, start the production server:

```bash
npm start
```

The app is now running on port 3000. Try `curl http://0.0.0.0:3000/` to verify.

Note:

1. Create a Linux system service to automatically restart the app if it crashes. 

2. Use a reverse proxy like NginX or Caddy to serve the application over HTTPS.


Check out [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
