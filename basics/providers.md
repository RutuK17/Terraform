## Terraform Providers ##

### Definition: ###
Providers are plugins that let Terraform interact with specific infrastructure platforms by translating configuration files into API calls.

### Purpose: ###
They serve as the bridge between Terraform and the underlying infrastructure (cloud, SaaS, or on-premises systems).

### Scope: ###
Providers aren’t limited to cloud vendors like AWS, Azure, GCP, or OCI.
There are many others for tools and platforms such as Kubernetes, Helm, VSphere, Artifactory, Spacelift, Aviatrix, and more.

### Functionality: ###
Each provider defines its own resources (things you can create/manage) and data sources (information you can query).
Example: The AWS provider includes resources for EC2, EBS, and ELB.

### Extensibility: ###
You can create your own provider if you have an API to interact with, but thousands already exist in the Terraform Registry (https://registry.terraform.io/browse/providers)



### References: ###

Provider - https://developer.hashicorp.com/terraform/language/providers
Article - https://techblog.flaviusdinu.com/terraform-from-0-to-hero-2-providers-8d2c97ef6cf1
AWS provider - https://registry.terraform.io/providers/hashicorp/aws/latest/docs
