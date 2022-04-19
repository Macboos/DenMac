up:
	#vcpid=$(shell aws ec2 describe-vpcs --filters "Name=isDefault,Values=true" | jq ".Vpcs[0].VpcId")
	#subnetid := `aws ec2 describe-subnets --filters "Name=vpc-id,Values=vpc-dd6958a4" | jq ".Subnets[0].SubnetId"`
	terraform apply --auto-approve

down:
	terraform destroy --auto-approve

init:
	terraform init