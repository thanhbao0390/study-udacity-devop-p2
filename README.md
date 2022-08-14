### Project Title - Deploy a high-availability web app using CloudFormation
Create cloudformation
	./create.bat CFBaoP2 network.yml network-parameters.json
	
Update cloudformation
	./update.bat CFBaoP2 network.yml network-parameters.json
	
Delete stack 
    aws cloudformation delete-stack --stack-name CFBaoP2


Create wweb
    ./create.bat CFBaoP2Web servers.yml server-parameters.json

	
Update cloudformation
    ./update.bat CFBaoP2Web servers.yml server-parameters.json
	
Delete stack 
    aws cloudformation delete-stack --stack-name CFBaoP2Web

### URL
    http://cfbao-webap-1ww4lp4w137fu-536422569.us-east-1.elb.amazonaws.com/


### Architecture
    InstagramWebApp.png

### Evidence CloudFormation stack
    CloudFormation-Stack.png