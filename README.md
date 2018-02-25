# udacity_deep_learning_playbook
An ansible playbook for spinning up Deep Learning EC2 instances. 

## Why make this playbook? 
I did several projects during the Udacity Machine Learning Engineering Nanodegree program that required spinning up an AWS EC2 instance capable of training deep learning models. I found the process of setting up 

## Pre-requisites
This playbook assumes... 
1. You have already created an AWS account. If not, go here https://aws.amazon.com/
2. You have already created a user under AWS Identity and Access Management (IAM). In addition, you have your AWS Access Key ID and AWS Secret Access Key from this process saved. For more instructions, go to https://aws.amazon.com/iam/
3. You have already configured your AWS CLI. If not, go to https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html


## How to use this playbook? 
1. Clone the repo. 
Easy enough. 

2. Activate the virtual environment. 
```
cd <path to cloned repo>
source deep-learning/bin/activate
```

3. Update the hosts file with the appropriate values relevant to your AWS account. 

4. Run the playbook
```
ansible-playbook -i hosts setup_dl_ec2.yaml
```

## How to contribute?
1. Clone on to your computer
2. Work on new branch
3. Push branch to origin and make pull request!
