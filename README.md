// Target - Kiratech Challenge

Create a Kubernetes Cluster using Terraform, Ansible and Helm.
The cluster must has three Virtual Machines: 1 Manager and 2 Workers deployed by Ansible.
Deploy one application composed by three services and a GUI reachable via browser.

// Requirements

Kubernetes Cluster must be created on a VM-based infrastructure deployed with Ansible.
The configurations have to guarantee the Kubernetes requirements.
Virtual Machines can be deployed with any tools.

The Kubernetes cluster provisioning must be done by provisioning a Terraform providers that:
1. Install 1 Manager and 2 Workers
2. Create a namespace called "kiratech-test"
3. Execute a Security Benchmark

The application must be deployed by using Helm.
The application must be composed at leat by three services.

// Versioning

Versioning in a public repository on GitHub

// Continuous Integration

Configuring a CI Pipeline using any tools

