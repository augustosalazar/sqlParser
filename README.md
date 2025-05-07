# SQL Parser


A React app that parses SQL queries and displays the parsed tree in a user-friendly format. The app is built using React, TypeScript, and Ant Design.

## Dev mode

```bash
 cd app
 nmp install
 npm run dev 
```

## Deployment

To deply the app, run the following command
```bash
 docker build -t sqli .
 docker run -d -it -p 5032:3000 --restart unless-stopped --name sql sqli