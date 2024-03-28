# Prisma Cloud GCP Organization Onboarding Cloud Formation Template Example
This is an example of a Terraform template generated from Prisma Cloud to onboard GCP Organization. The following items have been enabled as part of this onboarding:

Default/Mandatory:
* Misconfiguration (CSPM)
* Identity Security
* Threat Detection

Optional Security Capabilities:
* Agentless Workload Scanning
* Serverless Function Scanning

Optional security capabilities can be enabled/disabled as per organizations' needs and requirement.

Note: You will need to generate the Terraform template when you're onboarding GCP organization to your Prisma Cloud tenant. This serves as an example on the permission required for the integration to work. Also, the permission will be updated from time to time to include new services.