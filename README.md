# DotNet C# Application with Tests

## TAP Deployment Steps

### Create DotNet Pipeline
`kubectl apply -f csharp-weatherforecast/config/test-pipeline.yaml`

### Deploy App
`tanzu apps workload apply -f csharp-weatherforecast/config/workload.yaml`
