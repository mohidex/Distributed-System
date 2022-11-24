#### Characteristics of a Distributed System.

1. Service discovery: The nature of a distributed system is that there are multiple services that are interacting with one another. And these services should be as decooupled as possible, which means they don't need each other intrinsically, but they need to find each other. 

2. Load balancing: They can be scaled so that more resource will be provided for those services that are under pressuer. That means it have to some sort of a load balancing in place.

3. Distributed tracing and logging: Distributed logging is actually more of a centralized logging concept, where all of your services have the ability to send log message to a common location. As a service request goes from the original requester (the end user) through different services framework, it can have quite a long journey. So distributed tracing is way to trace the path of execution from the requester through all of the distributed services, and back to that requester when the response is finally available.

4. Service monitoring: The ability to monitor the services of a distributed system required. So it will know not only when new services are come up but also when service go down, both in a planed and an unplanned manner.
