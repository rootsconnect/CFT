# CFT
This CFT will stand up a new stack in AWS with the following network resources:
1x VPC 
2x Public Subnet (incl. 2x IGW attached to Public Subnets)
2x Private Subnet (incl. NAT Gateway to communicate to www)
2x EIP assigned to NAT Gateways
1x Public Routing Table (incl. Default-Route pointing to IGW)
2x Private Routing Table (incl. Default-Routes pointing to NAT Gateway)
1x NACL attached to all 4 Subnets
