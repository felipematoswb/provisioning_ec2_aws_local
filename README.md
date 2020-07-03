## provisioning instance on AWS with ANSIBLE

## steps
### install boto
### use credentials AWS
### configure variables
- instance_type: t2.micro
- sec_group_name: InfraAsCode
- image: ami-085925f297f89fce1
- keypair: my-keypar
- region: us-east-1
- count: 3 (number ec2)
- profile: default (if use profile aws configure)
