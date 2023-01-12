# Amazon Guarduty
* Machine learning to protect aws account
* inputs: VPC Flow logs, CloudTrail logs, DNS logs.
* notify: cloudwatch to: Lambda, SNS

# Aws Shield
* Standard: Protects from  SYN/UDP Floods, Reflection attacks and other layer 3/layer 4 attacks
* Advanced: Protects from DDoS

# Amazon Inspector
* Analize EC2 for known vulnerabilities

# Amazon Macie
* on S3 analize sensitive identify personal data (PII) and discover and notify Cloudwatch


# Aws Firewall Manager
* to manage ruls in all accounts on AWS organization
* Aws shield, Aws Waf, SG

# Aws WAF
* layer 7
* on ALB, Cloudfront, Api Gateway
* rules: ip adddress, http header, uri, for SQL inyection

# Cloud HSM
* As KMS but by hardware
* you managed encryptation keys not aws
* good for SSE-C

# KMS
* key rotation every 1 year automaticaly or manual


# Aws Secrets Manager
* meant for RDS
* force rotation of secrets
* secrets are encripted using KMS

# SSO
* support AD
* support SAML
* support AWS


