# AWS EC2 instance
you can create EC2 instance in joindevops using this module.

## inputs

* ami_id (optional) - AMI ID that need to be used by instance. Default is devops-practice i.e. sg-010de5f651406624d
* instance_type (optional) - instance type to bu used by instance, valid values are t3.micro, t3.small, t3.medium. Default is t3.micro
* sg_ids (required) - a list of SG IDs to attach instance
* tags (required) - a map of tags to be associated with instance

## outputs
* public_ip - public ip of the instance created
* privat_ip - private ip of the instance created
* instance_id - instance id of the instance created