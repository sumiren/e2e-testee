## Summary

This is e2e testee application.
Clone this repository and deploy the app to aws by npm command 'npm run deploy'.
The app enables you to try E2E test tools.

Note that you have to install
* Node.js
* AWS CLI
* AWS CDK CLI
* Vue CLI

And, you have to tell AWS CDK your AWS Environment.
One of the ways is defining AWS Profile on AWS CLI and setting AWS_PROFILE environment variable on terminal.

## Q & A

* Q1. What if I wanted to modify pages in order to confirm whether E2E tools are able to detect degressions?
  * Just modify source code and run another deploy command.
