# Benchmark Guidelines

- Identical enviornment in terms of Compute, Network and Storage for all Java frameworks including:
  - Cloud environment (AWS Resources)
  - Java Runtime ([OpenJDK 11](https://github.com/openjdk)) & Heap Configuration


# Benchmark Tool
- Use [ApacheBench](https://httpd.apache.org/docs/2.4/programs/ab.html)

```
ab -n 100000 -c 1000 <SERVER_ADDRESS>
```

-n: The number of requests to send
-t: A duration in seconds after which ab will stop sending requests
-c: The number of concurrent requests to make

# Benchmark Tests
