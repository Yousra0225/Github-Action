# Notes 

- GitHub Actions : 
     - is a plateform to automate developers workflows, while CI/CD is one of many workflows, there are other plateform like Jenkins ...
     - everything happened into a repo is an event, and every automated instruction applicated is a separate action
     - Combination of actions called worflow 
     - Workflows are sequence of automated actions that we launch when an event happened; for example CI/CD
     - Examples of even automating => action : 
          - Greetings Workflow when a contributer joined
          - 
- CI/CD it's the important part of DevOps
- Contiuous integration CI
- Continious Delivery/Deployment CD
- Piplines : runs a sequence of automated actions each time the code is updates
- C delevry (until tests) and c Deployment until the end

```bash
     [pull] => [build] => [test] => [deploy]
     -------   -------    -------   ------------
     | git |   |Maven|    |JUnit|   |Kubernetes|   #Examples
     -------   -------    -------   ------------
```

## Tools to be used :
- [Docker](https://github.com/Yousra0225/Docker-Cheatsheet)
- [Kubernetes](https://kubernetes.io/)
     - Manage of containers
     - Manage deployment     
- Jenkins