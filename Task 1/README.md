
## CASE-STUDY
Our architecture team have supplied us with this infrastructure diagram with an aim to fully automate the implementation using Infrastructure as Code and CI/CD.

![ECS infrastructure Diagram](./images/ecs_infra_diagram.jpg)

## Task 1: Infrastructure as Code Template

You have been asked to create a `yaml` formatted CloudFormation template **OR** a Terraform template for the above diagram. Our heros from the network team have already created the networking level components (like the VPC, Subnets, NAT Gateways for public internet routing) and have provided the required IDs and ARNs below:

### The Challenge
Create an Infrastructure as Code (IaC) template using the IDs provided below wherever necessary.

PublicSubnetIds:
  - "pub--7eqwhyn6rn"
  - "pub--54wxuuz4yz"
  - "pub--y5wdouvoar"

PrivateSubnetIds:
  - "priv--whyn6rn7eq"
  - "priv--uuz4yz54wx"
  - "priv--uvoary5wdo"

VpcId: "x567hhdz"

Route53HostedZoneId: "xcf4435z"

Route53HostedZoneName: "mmt_tech_test_zone"

AcmCertificateArn: "arn:aws:acm:eu-west-1:8877665544:certificate/123456789012-1234-1234-1234-12345678"
