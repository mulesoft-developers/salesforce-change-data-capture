<h1 align="center">
	<img
	width="150"
	src="/images/max-terminal.gif"></br>
	Subscribing to Change Data Capture Events with the Salesforce Connector<br>     
</h1>

<h4 align="center">
	<a href="#overview">Overview</a> |
	<a href="#installation-instructions">Install Me</a> |
	<a href="#contributing">Contribute</a>
</h4>
	
<h3 align="center">
	Learn how to subscribe to Salesforce CDC events in real-time and look at the message payload<br><br>
</h3>

## Tutorial and Video

For a step by step tutorial navigate to the MuleSoft developer website [here](https://www.youtube.com/watch?v=5Xd5B_twt9w)

For a video of the tutorial go [here](https://www.youtube.com/watch?v=5Xd5B_twt9w).

## Overview

In this tutorial, we’ll walk you through how you can subscribe to change data capture (CDC) events in Salesforce to exchange real-time data with external apps. You’ll learn how to :
- Enable change data capture events in Salesforce
- Use the Salesforce connector to subscribe to a Contact change event
- View the structure of a change data capture event in Anypoint Studio

> This sample application is designed to run on MuleSoft's Anypoint Platform.

## Installation Instructions

Install instructions

1. Download Anypoint Studio

<a href="https://www.mulesoft.com/lp/dl/studio" ><img width="250" src="/images/download-studio.png"><a>
	
2. Signup for a free [Salesforce Developer Edition Org](https://developer.salesforce.com/signup)

3. Clone this repository.

4. In Anypoint Studio, select `File` > `Import` > `Anypoint Studio` > `Anypoint Studio project from File System` and click Next.

5. Select the cloned repository in the Project Root and make sure to **uncheck** the `Copy project into workspace` option.
	
6. Click on Finish.	
	
7. Update your Salesforce Developer Edition Org credentials in the config.yaml file 
In Anypoint Studio's package explorer open **src/main/resources** open **local.secure.yaml** and update the username, password and token. Note that password and token should be encrypted (see video and tutorial above for details).
	
8. Add Runtime Configurations for env and secret.key variables. Set env to local and set secret.key to be the value used to encrypt your secure property parameters.

## Contributing

Contributions are what make the MuleSoft community such an amazing place. Any contributions you make are **greatly appreciated**.
	
See [contributing.md](/contributing.md) for the MuleSoft Developer principles.
