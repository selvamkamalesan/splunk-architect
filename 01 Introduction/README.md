# Describe a deployment plan
There are a few things that should be determined prior to deploying any new infrastructure. This includes:

* Deployment goals
* Number of users, user roles, support staff
* Topology of the current environment
* Planned topology for Splunk
* Data sources (where are we collecting logs from?)
* Data related policies (data retention, logging requirements, etc.)
* Splunk apps/add-ons needed for environment
* Education/training plan
* Deployment Schedule

When you're in an environment where there is an already existing Splunk infrastructure, all of the previous should be documented prior to any changes or upgrades.

Useful links: 
* [Plan a Deployment](https://docs.splunk.com/Documentation/Splunk/latest/Updating/Planadeployment)

# Define the deployment process
The Splunk deployment process is pretty straightforward. The most general phases include:
1. Infrastructure deployment (search heads, indexers, forwarders, etc.)
2. Data ingestion (data from forwarders, applications, etc. as well as data normalization and enrichment)
3. Knowledge object creation (searches, reports, dashboards, and alerts depending on use case)

There are more nuances in each of these phases, but this is typically how I would approach it.

Useful links:
* [Deployment Guide](https://www.splunk.com/themes/splunk_com/img/assets/pdfs/education/SplunkDeploymentGuide2_1.pdf)
