
LOAD BALANCER DNS NAME 
http://Jenny-WebAp-1HC487UQQT461-1551129960.us-east-1.elb.amazonaws.com


### Dependencies
##### 1. AWS account
You would require to have an AWS account to be able to build cloud infrastructure.

##### 2. VS code editor
An editor would be helpful to visualize the image as well as code. Download the VS Code editor [here](https://code.visualstudio.com/download).

##### 3. An account on www.lucidchart.com
A free user-account on [www.lucidchart.com](www.lucidchart.com) is required to be able to draw the web app architecture diagrams for AWS.


### How to run the supporting material?
You can run the supporting material in two easy steps:
```bash
# Ensure that the AWS CLI is configured before runniing the command below
# Create the network infrastructure
# Check the region in the create.sh file
./create.sh myFirstStack jennynetwork.yml jennynetworkparameter.json
# Create servers
# Change the AMI ID in jennyserver.yml
# Check the region in the update.sh file
./update.sh myFirstStack jennyserver.yml jennyserverparameters.json
```
