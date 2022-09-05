# How to get started on Architecture CyberSecurity



# Measure it!

Security is not a feature is a concern, which is co-related with the quality of your solution, what's the best way to know the quality? Measure it.

Start with the four key metrics (from DevOps Research and Assessment (DORA) )
* Deployment frequency:
* Lead time for changes
* Change failure rate
* Time to restore service


Locate your instrumentation points
* Commit timestamp
* Deployment timestamp
* Monitor service failures

Quality attributes
* Functional suitability
* Performance efficiency
  * Time behavior (Response time)
  * Resource utilization
  * Capacity (TPS - Throughput)
* Compatibility
* Usability

Testing Pyramid
* Base layer, made of the easiest tests, unit tests
* Middle layer, integration tests
* Top layer, security, performance E2E tests.

Measure code-related metrics
* Technical debt, including cohesion, modularity
