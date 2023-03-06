# Pipeline description
This file contains different steps took place inside the pipeline

## Pipeline steps
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