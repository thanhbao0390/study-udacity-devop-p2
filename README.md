
### Project Title - Deploy a high-availability web app using CloudFormation
Create cloudformation
	<code>./create.bat CFBaoP2 network.yml network-parameters.json</code>
	
Update cloudformation
	<code>./update.bat CFBaoP2 network.yml network-parameters.json</code>
	
Delete stack 
    <code>aws cloudformation delete-stack --stack-name CFBaoP2</code>


Create wweb
    <code>./create.bat CFBaoP2Web servers.yml server-parameters.json</code>

	
Update cloudformation
    <code>./update.bat CFBaoP2Web servers.yml server-parameters.json</code>
	
Delete stack 
    <code>aws cloudformation delete-stack --stack-name CFBaoP2Web</code>

### URL
    ![](http://cfbao-webap-1v5d8i1zi8vr0-1177904550.us-east-1.elb.amazonaws.com/)


### Architecture
    ![](https://raw.githubusercontent.com/thanhbao0390/study-udacity-devop-p2/main/InstagramWebApp.png)

### Evidence CloudFormation stack
    ![](https://raw.githubusercontent.com/thanhbao0390/study-udacity-devop-p2/main/CloudFormation-Stack.png)

### Output
    ![](https://raw.githubusercontent.com/thanhbao0390/study-udacity-devop-p2/main/Output.png)


