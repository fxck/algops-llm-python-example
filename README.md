```yaml
project:
  name: algops-llm-example

services:
  - hostname: python
    type: python@3.11
    buildFromGit: https://github.com/fxck/algops-llm-python-example
    enableSubdomainAccess: true
    envSecrets:
      WORKERS: 1
```
