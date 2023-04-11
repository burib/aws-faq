# ECS Fargate:

## Pros:
 - Serverless container management
 - Easy to set up and use
 - Lower costs for smaller workloads
## Cons:
 - Limited control over underlying infrastructure
 - Limited customization options
 - Limited scaling support
   - maximum number of tasks per account: 5,000 by default - [limits](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/service-quotas.html#service-quotas-fargate)
   - potential for slow scaling due to cold start time


# EKS:

## Pros:
 - More control over underlying infrastructure
 - More customization options
 - Better scaling support (recommended for handling over 10k requests per second)
 - Can handle complex workloads, including stateful apps
## Cons:
 - More complex to set up and use
 - Higher costs for smaller workloads
 - Requires more management of underlying infrastructure

# API Gateway:

## Pros:
 - Fully managed service
 - Easy to set up and use
 - Integrates with many other AWS services
 - Supports multiple protocols (REST, WebSocket, HTTP)
 - Good for building and deploying APIs quickly
## Cons:
 - Limited customization options for request/response processing
 - Higher costs for larger traffic volumes
 - Latency can be an issue for high-performance applications with high RPS.
