# Amazon Price Checker

Web scrapping. Find a product price on Amazon and email when price goes below a specified amount using node.js
by The Utopian Fool

🧠 Concepts Covered:

- Web scraping
- How to handle JavaScript rendered applications when web scraping
- Automatic email sending
- SendGrid integration
- Finding elements with Chrome dev tools

## Set up

Create folder for project and run below from terminal inside the project root folder. Run npm init to set up project with package.json file.

```
npm init
```

### Install dependancies

```
npm i nightmare @sendgrid/email
```

#### Nightmare 

Web scraping from websites that render on the frontend https://www.npmjs.com/package/nightmare
http://www.nightmarejs.org/

#### Sendgrid

Library to send and receive emails https://www.npmjs.com/package/@sendgrid/mail
https://sendgrid.com/docs/for-developers/

### Set up environment variables file

Allows us to set up environment variables in a .env file. (Create this file)

```
npm i dotenv
```


-----------------------------------------------------------------------------

## Development

### Run code in parser.js file

Run in terminal from root of project

```
node parser.js
```

### Set up sendgrid account and create api key

[Sendgrid](https://sendgrid.com/)

Place api key in .env file use .gitignore to hide .env file from git

```
SENDGRID_API_KEY=SG.24JUpB3sRAyoOfxjS6ABcA
```

### Use temporary email for testing

[Temp Mail](https://temp-mail.org/)




---------------------------------------------------------------

Thanks to Web Dev Simplified for the initial tutorial https://youtu.be/H5ObmDUjKV4
