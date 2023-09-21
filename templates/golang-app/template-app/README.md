# ${{values.name }} microservice

## Description

This is a microservice for ${{values.name }}. It is written in Go and created using Backstage scaffolder.

The project will be build using Tekton and deployed via Kubevela.

## Usage

### Docker

If you have docker installed, you can run the following commands to build and run the application locally.

```bash
docker build -t ${{values.name }} .
docker run -p 9090:9090 ${{values.name }}
```

### Local

If you have Go installed, you can run the following commands to build and run the application locally.

```bash
go run main.go
```
