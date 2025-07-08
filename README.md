# Datadog Agent for Render

Datadog helps you capture application traces and metrics that can help you improve the performance for your app.

You can set up a single Datadog agent to capture data for any number of services in your Render account.

This example deploys Datadog's Docker agent as a private service on Render. Once deployed, you can start sending APM/Distributed Tracing and DogStatsD metrics to your private service URL.

The URL will look like datadog-agent-lkyz with APM available on TCP port 8126 and DogStatsD on UDP port 8125.

You will need to configure your Datadog API key by setting the DD_API_KEY environment variable to your private service.
