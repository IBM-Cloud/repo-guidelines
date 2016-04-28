#'AppName' Overview

<Include an overview of the functionality which this sample is built for developers to leverage. Explain why this technology (i.e. service) is useful when developing web apps. You should also include Travis CI, Codeship, or other visual indicators of open-source tooling used to build and test your app.>

## Application Requirements
<List any requirements for using the app, like browser and version. Remove this section if it is not needed.>

## Running the app on Bluemix
<Either add a Deploy to Bluemix button or include detailed insructions on how to deploy the app to Bluemix after cloning the repo. You should assume the user has little to no Bluemix experience and provide as much detail as possible in the steps.>

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy)

1. Step 1
 
2. Step 2
	* Substep (a)
	* Substep (b)
3. Step 3

	```
	Your code here
	```

<Avoid directly referencing the Bluemix UI components so that ACE changes don't invalidate your README.>

## Run the app locally
<Include instructions on how to run the app on a user's local machine. Be sure to reference the technologies they might have to download for the application to run.>

## Decomposition Instructions
<Instructions on how a developer would take the sample application and extract the relevant code for reuse.>

## API documentation
<If the sample app or relevant service exposes an API, provide a short explanation of the API and how it is used in the sample. Link out to the published REST API documentation.>

## Contribute
<Note how you would like developers to contribute and/or log issues to your project. Also give steps for making pull requests. If your contribution directions become lengthy, break them out into a file called ‘CONTRIBUTING.md’ and link to this.>

## Privacy Notice
<If you are using the deployment tracker, you must include a privacy notice to let the user know that we are collecting deployment data.>

The 'AppName' sample web application includes code to track deployments to Bluemix and other Cloud Foundry platforms. The following information is sent to a [Deployment Tracker](https://github.com/cloudant-labs/deployment-tracker) service on each deployment:

* Application Name (application_name)
* Space ID (space_id)
* Application Version (application_version)
* Application URIs (application_uris)

This data is collected from the VCAP_APPLICATION environment variable in IBM Bluemix and other Cloud Foundry platforms. This data is used by IBM to track metrics around deployments of sample applications to IBM Bluemix. Only deployments of sample applications that include code to ping the Deployment Tracker service will be tracked.

<Include info on how to remove the deployment tracker from your app here.>

-
Use the below for Markdown formatting syntax:

#Header 1
## Header 2
### Header 3
#### Header 4

> This is a blockquote.
> 
> This is the second paragraph in the blockquote.

* list item #1
* list item #2

1. ordered item #1
2. ordered item #2

`This is a code snippet`

```
This is a code block
```

*This text will be italic*

**This text will be bold**

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell 

To create a hyperlink to www.github.com, with a link text that says, Visit GitHub!, you'd write this in Markdown: [Visit GitHub!](www.github.com)

### Useful links
[IBM Bluemix](https://bluemix.net/)  
[IBM  Bluemix Documentation](https://www.ng.bluemix.net/docs/)  
[IBM Bluemix Developers Community](http://developer.ibm.com/bluemix)