This repository is for Istio mesh service - Udemy course - https://www.udemy.com/course/istio-hands-on-for-kubernetes/

Course content
==============
Section 1 Course introduction - Course resource download
Section 2 Getting Started
Section 3 Installing a local Kubernetes environment
4. What to do if you need to install Kubernetes locally?
5. (Optional) Choosing between Docker Desktop and Minikube
6. (Optional) How to Install Docker Desktop
7. (Optional) How to Run Kubernetes in Docker Desktop
8. Extra note for Desktop users using a Mac with Apple Silicon (M1, M2, M3 etc)
9. (Optional) Installing Minikube
10. (Optional) Choosing a Minikube Driver

Section 4 Hands on Demo
11. What to expect in this section
12. Note for Docker Desktop Users
13. Getting Istio Running
14. Enabling Sidecar Injection
15. Visualizing the System with Kiali
16. Finding Performance Problems
    
Section 5 Introducing Envoy
17. Introducing Envoy - The Data Plane
18. The next lecture is optional!
19. Going Deeper into Envoy (Optional Video)

Section 6 Telemetry
20. Starting the Demo System
21. Kiali Deeper Dive
22. Kiali Dynamic Traffic Routing
23. Distributed Tracing Overview
24. Using Jaeger UI
25. Why you need to "Propagate Headers"
26. What happens if you don't propagate headers?
27. Metrics with Grafana

Section 7 Traffic Management
28. Introducing Canaries
29. Canaries with Replicas
30. Version Grouping
31. Elegant Canaries and Staged Releases
32. What is an Istio VirtualService?
33. VirtualService Configuration in yaml
34. What is an Istio DestinationRule?

Section 8 Load balancing
35. Session Affinity ("Stickiness")
36. What is Consistent Hashing useful for?

Section 9 Gateways
37. Reminder for Docker Desktop users - port-forwarding
38. Why do I need an Ingress Gateway?
39. Edge Proxies and Gateways
40. Prefix based routing
41. Subdomain Routing

Section 10 Dark Release
42. Using a browser extension to modify headers
43. If you have problems in the next section
44. Header Based Routing
45. Dark Releases for all Microservices

Section 11 Fault Injection
46. Fault Injection

Secrion 12 Circuit Braker
47. Cascading Failures
48. Configuring Outlier Detection
49. Testing Circuit Breakers

Section 13 Mutual TLS
50. Why is encryption needed inside a cluster?
51. How Istio can upgrade traffic to TLS
52. Enabling mTLS - it's Automatic
53. STRICT vs PERMISSIVE mTLS
54. STRICT mTLS Works in Both Directions

Section 14 Customizing nad installing Istio with istionctl
55. Quick note on "uninstall"
56. Introducing istioctl
57. Istio Profiles
58. Installing addons
59. Notes on the upcoming video
60. Tuning Profiles
61. Note on the upcoming video
62. Default vs Demo Profiles - CPU and Memory
63. Generating YAML Manifests

Section 15 Upgrading Istio
64. In-Place Upgrades
65. "Canary Upgrades" (Rolling Upgrades)
66. Live Cluster Switchovers (Alternative to the official upgrade paths)

Section 16 Goodbye!
