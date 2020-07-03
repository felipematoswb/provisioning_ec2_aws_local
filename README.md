## provisioning instance on AWS with ANSIBLE

### install boto
### use credentials AWS
### configure variables in "provisioning_ec2_aws_local/roles/create-instances/vars/main.yml"
- instance_type: t2.micro
- sec_group_name: InfraAsCode
- image: ami-085925f297f89fce1
- keypair: my-keypar
- region: us-east-1
- count: 3 (number ec2)
- profile: default (if use profile aws configure)
