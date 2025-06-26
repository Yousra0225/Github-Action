# Workflow File
*A workflow file is a YAML file where you define the events to listen for and the automated actions to run in response.*

## Syntax

## 1. The name of the workflow :
```yml
name: Java CI with Mavenecri # or title 
```

### 2. [Events](https://docs.github.com/en/actions/reference/events-that-trigger-workflows)
```yml
# Define events that should trigger the workflow bellow (ex: creating issue, contributer joining ...)
on:
    push: 
        branches: [master]
    pull_request:
        branches: [master]
```

### 3. Jobs 
```yml
