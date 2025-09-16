# web
Project
vpc.tf – Defines the main VPC with DNS support.
subnets.tf – Creates private, transit, cluster, and data subnets.
security_groups.tf – Sets up security groups for VPC endpoints, AD, RDP, and ICMP.
endpoints.tf – Configures VPC endpoints for S3 (Gateway), MGN, and EC2 (Interface).
route53.tf – Placeholder for Route53 DNS rules.
launch_template.tf – Basic EC2 launch template setup.
