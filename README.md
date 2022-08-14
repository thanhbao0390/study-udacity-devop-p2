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
    ![](http://cfbao-webap-1v5d8i1zi8vr0-1177904550.us-east-1.elb.amazonaws.com/ | width=100)


### Architecture
    ![](https://github.com/thanhbao0390/study-udacity-devop-p2/blob/main/InstagramWebApp.png | width=100)

### Evidence CloudFormation stack
    ![](https://github.com/thanhbao0390/study-udacity-devop-p2/blob/main/CloudFormation-Stack.png | width=100)

### Output
    ![](https://github.com/thanhbao0390/study-udacity-devop-p2/blob/main/Output.png | width=100)