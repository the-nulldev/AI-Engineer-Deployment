## Task Three — Refactoring to Cloud Services (tasks/task3.md)

### Description

So far, your application has been communicating locally with various services and components. Databases, caches, and even Langfuse. Since you're doing everything locally in your development environment, communication is easy — they just need to communicate over your local network.

However, after moving to a production environment, this will not be possible. Additionally, you need to handle aspects such as scaling and fault tolerance as you'll, hopefully, be receiving a lot of traffic from interested customers.

If you don't have the infrastructure to run everything in a local data center,  you would use cloud services. Cloud services come in many flavors. You can use a public cloud like AWS or Azure and create instances for your infrastructure. This gives you control over your applications, but the setup process and maintenance can be complex.

On the other hand, you can utilize SaaS (Software as a Service) and PaaS (Platform as a Service) solutions. These allow you to access cloud services without doing much of the heavy lifting. Your SaaS provider will take care of managing the infrastructure, upgrades, scaling, patches, and other operations. While these cloud models are easy to set up, you have no control over the infrastructure. This may not be ideal for data-sensitive workloads.

In this stage, you'll refactor your app to use cloud services instead of the local setup we've been using so far. Note that it is possible to move our entire infrastructure to a public cloud, such as AWS EC2 instances. However, to keep the setup simple, we will use managed services. We’ll use Qdrant Cloud, Redis Cloud, and Langfuse Cloud. For the Litellm proxy, try experimenting with EC2/ECS instances or a cloud provider like [Render](https://render.com/deploy?repo=https://github.com/BerriAI/litellm).

Once you’ve created accounts on those platforms and deployed the services, you will receive an API key and endpoint URL. Use those to access the services.

### Objectives

In this task, your work is to setup account you can use to access managed services for your application. All these services offer a free plan that should be enough for you to get started. The “Useful resources” section contains resources that will help you get started.

### Deliverables

Your code will not change. However, your environment set up will change because now your application will be using different access keys and host parameters.

### Docs

### Other useful articles