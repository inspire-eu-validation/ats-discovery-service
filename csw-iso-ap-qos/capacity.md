# QoS Capacity

**Purpose**: Verification whether the minimum number of served simultaneous requests to a Discovery Service according to the performance quality of service is 30 per second.

**Prerequisites**

**Test method**

Examine whether the minimum number of served simultaneous requests to a Discovery Service according to the performance quality of service is 30 per second. Capacity shall be measured consistently based on sample reference request packages to a given service. The amount of request per package shall be 30 per second and shall be issued every second during a measurement timeframe of 1 min. A measurement shall take place at least once before launching the service in a production environment and monitored at regular intervals thereof to ensure that the compliance with the capacity requirement is still ensured.

**Reference(s)**

* [TG DISC](http://inspire.ec.europa.eu/id/ats/discovery-service/3.1/csw-iso-ap/README#ref_TG_DISC), section 5;

**Test type**: Automated

**Notes**

The frequency of the capacity is recommended to be monthly. It is advised that the sample reference packages are composed of 10% from Get Discovery Service Metadata and 90% Discovery Metadata requests. The test may be performed automatically.

## Contextual XPath references

The namespace prefixes used as described in [README.md](http://inspire.ec.europa.eu/id/ats/discovery-service/3.1/csw-iso-ap/README#namespaces).

Abbreviation                                               |  XPath expression
---------------------------------------------------------- | -------------------------------------------------------------------------
