## JS Simple Micro Service Project

```
This is just simple apps for MicroService learning Project.
Frontend with ReactJS & Backend with NodeJS.

./client for Frontend with ReactJS || Running on Port 3000
./comments for Comments Backend with NodeJS || Running on Port 4001
./posts for Posts Backend with NodeJS || Running on Port 4000
./event-bus for Event-Bus Services || Running on Port 4005
./query for Data Query Services || Running on Port 4002

For K8s Cluster, there are added feature called "Moderation" it's running on Port 4003 [./moderation]
Moderation is filter service, word "orange" will be rejected if you use a Moderation service.
```

## Important
```
If you don't want to use EventBus services, you can replace index.js on posts and comments directory with index.js on ./backup directory.
If you don't want to use Moderation services, you can deploy clientnomod-depl.yaml & commentsnomod-depl.yaml on infra k8s.
If you want to deploy on K8s, please replace all index.js with index.js on ./index-k8s directory first, then rebuild image.
```

## Documentation ?
```
Complete documentation is in each folder.
```

## Warning
```
Dont forget to run npm install first.
$ npm install

Then, if you want to run :
$ npm start

Also, if you want to build a project :
$ npm run build
```

## Build on Docker
```
All directories have been given Dockerfile, please build a new image.
$ docker build .
```
