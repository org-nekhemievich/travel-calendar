# Travel Calendar

[![licence mit](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](http://hemersonvianna.mit-license.org/)
[![GitHub issues](https://img.shields.io/github/issues/nvich/travel-calendar.svg)](https://github.com/nvich/travel-calendar/issues)
![GitHub package.json version](https://img.shields.io/github/package-json/v/nvich/travel-calendar.svg)
![GitHub Release Date](https://img.shields.io/github/release-date/nvich/travel-calendar.svg)
![GitHub top language](https://img.shields.io/github/languages/top/nvich/travel-calendar.svg)
![GitHub repo size](https://img.shields.io/github/repo-size/nvich/travel-calendar.svg)
![GitHub All Releases](https://img.shields.io/github/downloads/nvich/travel-calendar/total.svg)

## Install

```
npm install
```

## Usage

```
mongod
```
```
mongoimport --db travel-calendar --collection travels --file ./resources/data/travel-calendar/travels.json
mongoimport --db travel-calendar --collection users --file ./resources/data/travel-calendar/users.json
```

### Development

```
npm run start:dev
```

### Production

```
npm start
```

## API

### Get All
```
GET - http://localhost:3000/admin/travels
```

### Create ID
```
POST - http://localhost:3000/admin/travels
```

### Get ID
```
GET - http://localhost:3000/admin/travels/:id
```

### Update Id
```
PUT - http://localhost:3000/admin/travels/:id
```

### Delete Id
```
DELETE - http://localhost:3000/admin/travels/:id
```
