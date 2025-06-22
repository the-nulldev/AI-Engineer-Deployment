## Refactoring to Cloud Services

### Description

So far, your application has been communicating locally with various services and components. Your vector and Redis databases and also Langfuse. Since you're doing everything locally in your development environment, communication is easy — they just need to communicate over your local network. 
However, after moving to a production environment, this will not be possible. Additionally, you need to handle aspects such as scaling and fault tolerance as you'll, hopefully, be receiving a lot of traffic from interested customers.

If you don't have the infrastructure to run everything in a local data center,  you would use cloud services. Cloud services come in many flavors. You can use a public cloud like AWS or Azure and create instances for your infrastructure. This gives you control over your applications, but the setup process and maintenance can be complex.

On the other hand, you can utilize SaaS (Software as a Service) and PaaS (Platform as a Service) solutions. These allow you to access cloud services without doing much of the heavy lifting. Your SaaS provider will take care of managing the infrastructure, upgrades, scaling, patches, and other operations. While these cloud models are easy to set up, you have no control over the infrastructure. This may not be ideal for data-sensitive workloads.

In this stage, you'll refactor your app to use cloud services instead of the local setup we've been using so far. Note that it is possible to move our entire setup to a public cloud, such as using AWS EC2 instances. However, to keep the setup simple, we will use managed services. We’ll use Qdrant Cloud, Redis Cloud, and Langfuse Cloud. If you used the Litellm proxy for cost management, try experimenting with using EC2/ECS instances or a cloud provider like [Render](https://render.com/deploy?repo=https://github.com/BerriAI/litellm).

Once you’ve created accounts on those platforms, you will receive an API key and endpoint URL. Next, update your .env so that your code uses the new API keys and URLs. Note that the code will not change, but the environment setup will change. The code will now use the new API keys and URLs to communicate with the cloud services. Note that there is also additional setup you need to do. For example, for Qdrant, you will also need to create a collection and upload your data. 

### Objectives

In this task, your work is to set up accounts you can use to access managed services for your application. All these services offer a free plan that should be enough for you to get started. The “Useful resources” section contains resources that will help you set things up.

### Deliverables

Your code may or may not change. However, your environment set up will change because now your application will be using different access keys and host parameters.

### Docs

### Other useful articles