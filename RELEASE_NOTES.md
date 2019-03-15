#### 0.2.0 March 15 2019 ####
**Now running on Akka.NET v1.3.12**


**Feature release, Akka.HealthCheck.Persistence** 

New package release that introduces liveness implementation intended for use with Akka.Persistence. 


**Project name change for Akka.Cluster**

The project name and files has been change from Akka.Cluster.HealthCheck to Akka.HealthCheck.Cluster for faster search and for name continuity. 


**Socket probe transport update**

Resolves bug issue with incoming connection request. The Socket Status Transport code has been modify to  correctly accept/handle incoming connections. It has also been modify to properly dispose resources when done. 

[See the full Socket Status Transport modification here](https://github.com/petabridge/akkadotnet-healthcheck/issues/21)
