# Release Note - Alpha (preview)

### Integration with customer’s source control management (SCM) tool

#### Github
Using aku.io Github Oauth token
 
#### Other providers
Not available in this release

### Integration with customer’s infrastructure



#### Amazon Web Services (AWS)
- Using IAM Role with specific permissions granted to aku.io to provision and configure specific types of resources

#### Other providers
Not available in this release

### Build Module

Supported applications

#### PHP
- Supported runtime versions <br>**7.1.32, 7.2.33, 7.3.7**

- Supported test frameworks
<br>**phpunit, codeception**

- Package manager
<br>**composer**

#### Go
- Supported runtime versions: 
<br>**1.11.13, 1.12.10**

- Supported test frameworks
<br>**go testing (built-in)**

- Package managers
<br>**go modules (built-in)**

#### Python
- Supported runtime versions: 
<br>**3.5.7, 3.6.9, 3.7.4**

- Supported test frameworks
<br>**unittest, pytest, nose2**

- Package managers
<br>**Pip**

#### Node.js
- Supported runtime versions: 
<br>**10.17.0, 12.13.0**

- Supported test frameworks
<br>**mocha, chai, jest, jasmine**

- Package managers
<br>**npm, yarn**

#### React
- Supported test frameworks
<br>**react-scripts test**

- Package managers
<br>**npm, yarn**


### Deploy Module

#### Amazon Web Services (AWS)

Supported services

- **Elastic Compute Cloud (EC2)**
		
  - Supported deployment strategies
  <br>*Recreate (direct update)*


- **Elastic Beanstalk**
		
  - Supported deployment strategies
  <br>*Recreate (direct update), blue-green*
	
- **Elastic Container Service (ECS)**
		
  - Supported deployment strategies
  <br>*Recreate (direct update), blue-green*

#### Other providers
Not available in this release
