# Google Cloud platform.

## Cloud Computing.
  - On demand self service
  - Broad network access.
  - Resource Pooling.
  - Rapid elasticity.
  - Measured Service.

## Google Cloud Platform provides:
  - Compute Engine - Infrastructure As A Service.
  - Kubernetes Engine - Hybrid
  - App Engine - Platform As A Service.
  - Cloud functions - Serverless Logic.
  - Managed Services - Automated Elastic Resources.

## Getting Started with GCP
  Cloud Security requires collaboration.
  * Google is responsible for managing its infrastructure security.
  * You are responsible for securing your data.
  * Google helps you with best practices, templates, products and solutions.
 
 Projects have three identifying attributes:
  * PROJECT ID - Globally Unique - Chosen by you - Immutable
  * PROJECT NAME - Need not be unique - Chosen by you - Mutable
  * PROJECT NUMBER - Globally Unique - Assigned by GCP - Immutable

  IAM - Identity Access management:
  Defines ` who` and `what` operations members can carryout on `resources`.
  IAM primitive role offers fixed, coarse-grained level of access.

  Owner: 
    * Invite members 
    * Remove members
    * Delete projects
  Editor:
    * Deploy applications
    * Modify Code
    * Configure services
  Viewer: 
    * Read-only access
  Billing administrator:
    * Manage billing
    * Add and remove administrators
 
 IAM Resource hierarchy (example):
 Policy Inheritance:  Organization -> Project -> Resources
 * A policy is set on a resource. 
  * Each policy contains a set of rules and role members
 * Resource inherits policies from parents
  * Resource policies are union of parents and resource.
 * A less restrictive parent policy overrides a more restrictive resource policy.


 
