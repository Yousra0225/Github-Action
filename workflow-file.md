# Workflow File
*A workflow file is a YAML file where you define the events to listen for and the automated actions to run in response.*

## Syntax

## 1. The name of the workflow :
```yml
name: Java CI with Maven # title 
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
# 
jobs: # job groups a set of actions that will be executed
    build: # name of the jobs (arbitrary)
    run-on: ubuntu-latest # operating system ex: windows-latest macos-latest ...
    steps: # liste of step to be followed 
    - uses: actions/checkout@v2 # to use a github action already exists in the repository 
                    # actions: where predefined actions are hosted
    - name: run-tests # name of the action
    - run: java -jar test4poo.jar poo.* #runing a command ex: linux command 
```