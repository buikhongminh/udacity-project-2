Deploy Static Website on AWS

In this project, you will deploy Infrastructure As Code 

The files included are: 
1. architecture: 
    - contain architecture diagram
2. cloudFormationScript:
    - It contains the essential files (.yml, .json, .bat, and .sh)
3. screensShoot

### How to run the project?
You can run the supporting material in two easy steps:
```bash
.\cloudFormationScript\create.bat udagramServer .\servers.yml .\servers-parameters.json --region us-east-1
.\cloudFormationScript\create.bat udagramNetwork .\network.yml .\network-parametres.json --region us-east-1
.\cloudFormationScript\update.bat udagramServer .\servers.yml .\servers-parameters.json --region us-east-1
```

### Web Application
![web](http://udagr-webap-8mnz9k3oudve-1130216297.us-east-1.elb.amazonaws.com)