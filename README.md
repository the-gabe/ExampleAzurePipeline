# This is an example of how to use Azure Pipelines

This workflow will only execute if tags begin with:

```
    - ExampleProject-prod-*
    - ExampleProject-uat-*
    - ExampleProject-dev-*
    - ExampleProject2-prod-*
    - ExampleProject2-uat-*
    - ExampleProject2-dev-*
```

Tags are made in the format of A-B-C. Where A is the subproject target (e.g ExampleProject2),
B is the deployment environment (e.g dev) and C is an arbitrary versioning string (e.g 1.1).
