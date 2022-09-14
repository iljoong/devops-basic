# Sample dotnet code for DevOps HoL (Basic)

![devops-pipeline](./devops-pipeline.png)

## Local build & test

Build and run

```
dotnet build
dotnet run
```

Test

```
curl http;//localhost:5000
```

Publish app

```
dotnet publish -c Release -o out
```

## Pipeline samples

- pipeline using MSFT-hosted agent: [build-pipeline.yml](./pipelines/build-pipeline.yml)
- pipeline using self-hosted agent: [build-pipeline_private.yml](./pipelines/build-pipeline_private.yml)
