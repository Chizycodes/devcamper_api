# DevCamper API

> Backend API for DevCamper application, which is a bootcamp directory website

## Usage

Update the values/settings of config/config.env to your own

## Install Dependencies

```
npm install
```

## Run App

```
# Run in dev mode
npm run dev

# Run in prod mode
npm start
```

## Database Seeder

To seed the database with users, bootcamps, courses and reviews with data from the "\_data" folder, run

```
# Destroy all data
node seeder -d

# Import all data
node seeder -i
```

## Demo

The API is live at [https://devcamper-api-esuh.onrender.com](https://devcamper-api-esuh.onrender.com)

Extensive documentation with examples [here](https://documenter.getpostman.com/view/21871844/2s9XxtwusL)

- Version: 1.0.0
- License: MIT
- Author: Joy Okwudire
