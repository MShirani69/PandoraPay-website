# Zero Website

Just the landing page for Zero

## Requirements

Node.js

## Installation

```
npm install
```

## Running

```
npm run dev
```

## Deploy

```
npm run build
npm run start
```


## Deploy PM2

build it

```
npm run build
pm2 start npm -- start
pm2 restart `processId` --name front
```

new version

```
npm run build
pm2 restart front
```