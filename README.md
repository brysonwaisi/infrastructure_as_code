### Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the code for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:

### Udagram Infrastructure
![udagram-diagram] (https://github.com/brysonwaisi/infrastructure_as_code/blob/master/final-project/Udagram%20.png)
#### network.yml and server.yml
Contains CloudFormation code written using this YAML template for building the cloud infrastructure.

#### parameters.json
We use a JSON file for increasing the generic nature of the YAML code. For example, the JSON file contains a "ParameterKey" as "EnvironmentName" and "ParameterValue" as "UdacityProject". 

In YAML code, the `${EnvironmentName}` would be substituted with `UdacityProject` accordingly.
