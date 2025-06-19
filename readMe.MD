#AWS ec2 instance
you can use ec2 instance in joindeovps by module

#inputs
*ami_id (oprional) - AMI ID that needs to be used by instace default is ami-09c813fb71547fc4f
*instance type (oprional)- instance type used ny instance. it must be t3.small,t3.micro,t3.medium by default is t3.small
*sg_ids(required)-list of security ids to attach  instance
*tags(required)-A map of tag to be associated with instance

##outputs

*pubilc_ip - public ip of the instance
*private_ip - private of the instnace
*instance_id - instance id of the instance