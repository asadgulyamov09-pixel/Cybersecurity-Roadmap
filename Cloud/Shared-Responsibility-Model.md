# Shared Responsibility Model

## Overview

Cloud security responsibilities are shared between the cloud provider and the customer.

Cloud providers protect the infrastructure of the cloud, while customers are responsible for securing what they place inside the cloud environment.

---

# AWS Responsibilities

AWS is responsible for:
- physical datacenters;
- hardware;
- networking infrastructure;
- physical security;
- cloud availability.

AWS protects the infrastructure that runs cloud services.

---

# Customer Responsibilities

Customers are responsible for:
- passwords;
- MFA;
- IAM permissions;
- uploaded data;
- operating systems;
- applications;
- cloud configurations.

Customers must properly secure their cloud environments.

---

# Common Misunderstanding

One of the most common misconceptions is:

“AWS handles all security.”

In reality, cloud security is shared.

Improper customer configurations may still lead to:

- data leakage;
- unauthorized access;
- cloud breaches.

Example

If a company creates a public S3 bucket and sensitive data leaks, the customer is usually responsible because the cloud storage was configured incorrectly.

Security Controls

Important controls include:

- MFA;
- least privilege;
- monitoring;
- logging;
- access reviews;
- strong passwords.
