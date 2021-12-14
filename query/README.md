## Data Query Services

```
This is Data Query Micro Services Powered by NodeJS.

Run:
$ npm install
$ npm start
Access on http://localhost:4002

Build:
$ npm run build
```

## Docker Build Image
```
$ docker build -t query_image_name .
```

## Docker Run Image
```
If you want to acces on port 80, just port forward like this :
$ docker run -d -p 80:4002 query_image_name
```