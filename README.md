Build Data Pipelines with Airbyte
---

This project focuses on building data pipelines with Airbyte.

For more information see: https://docs.airbyte.com/deploying-airbyte/local-deployment


# Prerequisites
- Docker
- PostgreSQL
  
# Local Deployment

Install ```Docker Engine``` and the ```Docker Compose plugin``` on your workstation.
After Docker is installed, you can immediately get started locally by running:

```
# clone Airbyte from GitHub
git clone --depth=1 https://github.com/airbytehq/airbyte.git

# switch into Airbyte directory
cd airbyte

# start Airbyte
./run-ab-platform.sh
```

