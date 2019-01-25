# deeplearningIEEE
Repository for an IEEE paper proposing a hybrid-approach for scaling deep learning models

Abstract— We are proposing a hybrid-approach to scaling
Deep Learning models, supporting both occasional prediction
requests and sustained high-throughput workloads with large
peaks. The approach consists of 3 components: an intelligent
load balancer (prediction, health monitor), a cluster of virtual
machines and a serverless infrastructure. State-of-the-art DL
services deploy their models on clusters of VMs; when experiencing
an unexpected high number of requests, scaling-gaps
lead to the un-availability in these services. The goal of this
approach is to guarantee the availability and low latency of
a DL service at any given time, while operating with costefficiency.
