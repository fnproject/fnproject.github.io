# Fn Project

The container native, cloud agnostic serverless framework.

## Quickstart

```sh
# Install command line tool:
curl -LSs https://raw.githubusercontent.com/fnproject/cli/master/install | sh
# Set your Docker Hub username
export FN_REGISTRY=<DOCKERHUB_USERNAME>

# Start server:
fn start

# Open a new console, then:

# Create a function
mkdir myfunc
cd myfunc
fn init --runtime go

# Test your function
fn run

# Deploy your function
fn deploy myapp

# Call your function:
curl http://localhost:8080/r/myapp/myfunc
# or:
fn call myapp /myfunc
```

Boom.
