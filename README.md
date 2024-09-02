# YelpCamp

This website is designed for camping enthusiasts. Users can share their camping experiences by posting descriptions, images, locations, and, if applicable, pricing details. It also allows others to leave reviews. A map feature is included, which pins each campsite, giving visitors a clear idea of where it is located.

Before the `Installation` I want to let you know that you can use the website link to see what it does without downloading anything.
P.S.: It will take like 1 min to load the website.

## Used

I used Node.js for this web app.
For the database I used MongoDB.
For styling I used Bootstrap 5.

## Installation

Use the npm to install all the packages:

```bash
npm install express@4.19.2
```

```bash
npm install express-session@1.18.0
```

```bash
npm install express-mongo-sanitize@2.2.0
```

```bash
npm install ejs@3.1.10
```

```bash
npm install ejs-mate@4.0.0
```

```bash
npm install dotenv@16.4.5
```

```bash
npm install mongoose@8.5.3
```

```bash
npm install connect-mongo@3.2.0
```

```bash
npm install helmet@7.1.0
```

```bash
npm install joi@17.13.3
```

```bash
npm install method-override@3.0.0
```

```bash
npm install connect-flash@0.1.1
```

```bash
npm install cloudinary@1.41.3
```

```bash
npm install multer@1.4.5-lts.1
```

```bash
npm install multer-storage-cloudinary@4.0.0
```

```bash
npm install passport@0.7.0
```

```bash
npm install passport-local@1.0.0
```

```bash
npm install passport-local-mongoose@8.0.0
```

```bash
npm install sanitize-html@2.13.0
```

```bash
npm install @maptiler/client@1.8.1
```

## Usage

First open `app.js` file and change the `const dbUrl = process.env.DB_URL;` at line 22 with `const dbUrl = 'mongodb://127.0.0.1:27017/yelp-camp';`.
Then run:

```bash
nodemon app.js
```

## Repository

The repository is closed because the project came to an end.
