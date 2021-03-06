
# Getting started

```bash

# Install
npm install -g serverless

serverless
sls

```

# Create a project

```bash

# Create a new project
serverless create --template aws-nodejs
sls create -t <template_type> --name <service_name>
sls create -t aws-nodejs -n simple
```

# Deploy

```bash

sls deploy --function <function_name>
sls deploy -f hello
```

# Invoke function

```bash

# Call locally
sls invoke local -f <function_name>

# Call deployed
sls invoke -f <function_name>

# Check log output for deployed function
sls logs -f <function_name>

```
