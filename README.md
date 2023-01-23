# Benchmark Guidelines

- Identical enviornment in terms of Compute, Network and Storage for all Java frameworks including:
  - Cloud environment (AWS Resources)
  - Java Runtime ([OpenJDK 11](https://github.com/openjdk)) & Heap Configuration


# Benchmark & Monitoring Tools
- [Grafana K6](https://k6.io/open-source/) - for load testing
- [Grafana Cloud](https://grafana.com/products/cloud/) - for monitoring CPU & Memory Usage
- [Opentelemetry](https://opentelemetry.io/) - to instrument, generate, collect, and export telemetry data (metrics, logs, and traces)

Other options considered:
- [ApacheBench](https://httpd.apache.org/docs/2.4/programs/ab.html)
- [Hey] (https://github.com/rakyll/hey)

# Benchmark Metrics to Measure

