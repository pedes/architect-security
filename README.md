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


To define security, it has become common to use Confidentiality, Integrity and Availability, also known as the CIA triad.

Authentication usually performed with something that you know, you have and you are (like biometrics/fingerprints)

Identify
- Risks
- Vulnerabilities
- Likelihood
- Threats


Service-Level Agreement (SLA)

The cloud computing service-level agreement (cloud SLA) is an agreement between a cloud service provider and a cloud service customer based on a taxonomy of cloud computing– specific terms to set the quality of the cloud services delivered. It characterizes quality of the cloud services delivered in terms of a set of measurable properties specific to cloud computing (business and technical) and a given set of cloud computing roles (cloud service customer, cloud service provider, and related sub-roles).

Think of a rule book and legal contract—that combination is what you have in a service-level agreement (SLA). Let us not underestimate or downplay the importance of this document/ agreement. In it, the minimum level of service, availability, security, controls, processes, communications, support and many other crucial business elements are stated and agreed to by both parties.  

The purpose of an SLA is to document specific parameters, minimum service levels and remedies for any failure to meet the specified requirements. It should also affirm data ownership and specify data return and destruction details. Other important SLA points to consider include the following:

    Cloud system infrastructure details and security standards
    Customer right to audit legal and regulatory compliance by the CSP         
    Rights and costs associated with continuing and discontinuing service use
    Service availability
    Service performance
    Data security and privacy
    Disaster recovery processes
    Data location
    Data access
    Data portability
    Problem identification and resolution expectations
    Change management processes
    Dispute mediation processes
    Exit strategy 



## References
- https://www.cisa.gov/free-cybersecurity-services-and-tools
