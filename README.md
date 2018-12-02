# Neeta Homepage

This is the repo for Neeta Madar website. The project is a static website and can be accessed at [neetamadahar.com](https://neetamadahar.com).
This homepage acts as

## Architecture

The project is served on an S3 bucket and acts as an independent site (yoga site) and as a second-level page to neetamadahar.com.

## Prerequisites

- NodeJS
- NPM

## Install dependencies

```
npm start
```

## Startup

To startup the project run...

```
npm start
```

## Deployment

The site will deploy automatically using CircleCI when the master branch is tagged with a version number such as `0.0.1`.
