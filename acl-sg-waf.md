# SECURITY

## Security Groups (EC2 level)
* Only allow rules  
* Is stateful (when we init a connection it allows return connection also if we allow)
* Inbound is blocked for default
* Outbound is allowed by default

## NACL (Subnet level)
* Allow and deny rules
* Is stateless (no return traffic allowed by default)
* Default NACL: Inbound and outbound is allowed all by default
* New NACL: deny all
