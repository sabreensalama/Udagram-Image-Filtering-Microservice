# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

# URL of ElasticBeanstalk
image-filter-microservice-dev.us-east-1.elasticbeanstalk.com 


## Tasks

### Setup Node Environment

You'll need to create a new node server. Open a new terminal within the project directory and run:

1. Initialize a new project: `npm i`
2. run the development server with `npm run dev`

### Create a new endpoint in the server.ts file

The starter code has a task for you to complete an endpoint in `./src/server.ts` which uses query parameter to download an image from a public URL, filter the image, and return the result.

We've included a few helper functions to handle some of these concepts and we're importing it for you at the top of the `./src/server.ts`  file.

```typescript
import {filterImageFromURL, deleteLocalFiles} from './util/util';
```

### Deploying your system

Follow the process described in the course to `eb init` a new application and `eb create` a new environment to deploy your image-filter service! Don't forget you can use `eb deploy` to push changes.

## Output
![elasticbeanstalk output](https://github.com/sabreensalama/Udagram-Image-Filtering-Microservice/blob/master/deployment_screenshots/deployment-ok)

![example of filtering ](https://github.com/sabreensalama/Udagram-Image-Filtering-Microservice/blob/master/deployment_screenshots/Screenshot%20from%202020-07-25%2017-07-07.png)

