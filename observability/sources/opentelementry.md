# OpenTelementry

Connecting to DTZ through OpenTelemetry can be done by configuring the OTEL-contrib agent with the following exporter settings.

```
    exporters:
      otlphttp:
        endpoint: "https://o11y.dtz.rocks/otel"
        headers:
          x-dtz-context: 00000000-0000-0000-0000-000000000000
          x-api-key: 00000000-0000-0000-0000-000000000000

```

