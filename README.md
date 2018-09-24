# My Azure Service Fabric Samples
This repo contains a number of Azure Service Fabric samples I have created over time. Please refer to the [official samples](https://github.com/Azure-Samples?q=service-fabric&type=&language=) for general code samples. The ones here target specific application, technology, or deployment scenarios. Typically, these are one-off projects and are not maintained over time for newer Service Fabric SDKs or .NET/.NET Core releases.

## [OwinAppInsightsApplication](https://github.com/joergjo/AzureServiceFabricSamples/tree/master/OwinAppInsightsApplication)
This sample shows how to configure Application Insights for a OWIN based ASP.NET Web API for all sorts of telemetry, *including* request telemetry and live metrics. To run the sample, simply add your Application Insights Instrumentation Key in `ApplicationInsights.config` where it says `[INSERT AI KEY]`.  
