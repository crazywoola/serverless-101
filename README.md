# serverless-101

## Create your first function

```bash
fn init --runtime node nodefn
```

## Deploy your application

```bash
# create a application to contain functions
fn create app demoapp
# deploy a function to local fn server
fn --verbose deploy --app demoapp --local
```

## Call your function

```bash
fn invoke demoapp nodefn
```