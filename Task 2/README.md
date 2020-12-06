## Task 2: Consuming AWS SSM Parameters

### Context
The networking team have gone above and beyond and started an innitiative of de-coupling resources created by them (like VPCs and Subnets) with supporting infrastructure which is created by engineers in our organisation.

### The Challenge
In order for them to succeed at this, you have been asked to replace any use of the IDs which were provided to you in your first task with resolved SSM Parameter values for the below paths:


PrivateSubnetIdSSM: /mmt/subnets/private/subnet-ids

PublicSubnetIdSSM: /mmt/subnets/public/subnet-ids

VpcIdSSM: /mmt/vpc/vpc_id

Route53HostedZoneIdSSM: /mmt/dns/r53_zone_id

Route53HostedZoneNameSSM: /mmt/dns/r53_zone_name

AcmCertificateArn: /mmt/acm/tech_test_ssl_arn
