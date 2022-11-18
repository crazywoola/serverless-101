# serverless-101

## Create your first function

```
fn init --runtime node simpleNodeFn
```

## Deploy your application

```
# create a application to contain functions
fn create app simple-application
# deploy a function to local fn server
fn --verbose deploy --app simple-application --local
```