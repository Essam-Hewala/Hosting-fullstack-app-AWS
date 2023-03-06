# Udacity Full-Stack Application hosting (Udagram)


### **Project overview**

Udagram is provided bu Udacity as an alternative starter project. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

### **Dependencies**

```
- Node v14.15.1 (LTS)
- npm 6.14.8 (LTS)
- AWS CLI v2
- A RDS database running Postgres.
- A S3 bucket for hosting uploaded pictures.
```


## Hosted production application

You can navigate to this application through this URL [Udagram](http://storefront-udacity.s3-website.us-east-2.amazonaws.com)

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.


## License

[License](LICENSE.txt)

## Documentation Dependecies 
dependencies for both front-end application and API back-end application.

## Global dependencies
- Node v14.15.1 (LTS)
- npm 6.14.8 (LTS)
- AWS CLI v2
- A RDS database running Postgres.
- A S3 bucket for hosting uploaded pictures.

# Pipline Description 
Pipeline contains 2 steps (Build, Deploy)

### 1. Build
This step contains needed actions to run the application (both front and back end) on CircleCI containers:

1. Install Front-End Dependencies.

Here we are installing all required dependencies for front-end application.

2. Install API Dependencies.

Here we are installing all required dependencies for back-end application.

3. Front-End Lint.

Running lint aginst front-end application files.

4. Front-End Build.

Running build commands inside CircleCI computer for front-end application.

5. API Build.

Running build commands inside CircleCI computer for back-end application.

### 2. Deploy
This step contains needed actions to deploy these applications to AWS different services (S3, EB).


