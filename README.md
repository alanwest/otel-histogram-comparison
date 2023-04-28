# OpenTelemetry Histogram Comparison

This repo contains an example app using OpenTelemetry .NET to compare
explicit-bounds histograms to exponential histograms.
The code is ported from this
[blog post](https://newrelic.com/blog/best-practices/opentelemetry-histograms).

Run:

```shell
export OTEL_EXPORTER_OTLP_ENDPOINT=https://otlp.nr-data.net:4317
export OTEL_EXPORTER_OTLP_HEADERS=api-key=<your_license_key>
dotnet run
```
