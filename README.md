### :octocat: [kyhau.github.io](https://kyhau.github.io) | [gist](https://gist.github.com/kyhau)

<img align="right" width="180" src="image/aws_community_builder_badge.png" />

## Table of Contents

- [AWS Projects](#aws-projects)
- [Data Visualisation and Graphic Source Processing Projects](#data-visualisation-and-graphic-source-processing-projects)
- [Other Projects](#other-projects)
- [Blogs and Notes](#blogs-and-notes)

---
## AWS Projects

| Project | Topics |
| :--- | :--- |
| [aws-tools](https://github.com/kyhau/aws-tools) <br/> Some of my tools and sample code for building with AWS. | CDK, Bash, Powershell, Python |
| [saml2aws-multi](https://github.com/kyhau/saml2aws-multi) </br> An easy-to-use command line interface to support login and retrieve AWS temporary credentials for multiple roles of different accounts with saml2aws. | saml2aws, Python |
| [slack-command-app-cdk](https://github.com/kyhau/slack-command-app-cdk) <br/> A Slack App/Bot (with CDK v2 and [sam-beta-cdk](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-cdk-getting-started.html)) that can handle requests triggered from a Slack Command which will take longer than 3 seconds to process, and posts the details back to the user. | Slack-bot, API Gateway, Lambda, Python, CDK v2, sam-beta-cdk, SAM |
| [aws-cognito-auth-lambda-nodejs](https://github.com/kyhau/aws-cognito-auth-lambda-nodejs) <br/> Node.js code that can be deployed to AWS Lambda, implements the "authenticate" part of the Amazon Cognito service. | Cognito, JWT, nodejs |
| [aws-cognito-token-verification-serverside](https://github.com/kyhau/aws-cognito-token-verification-serverside) <br/> Python implementation to process the Amazon Cognito ID token and the access token on the server side. | CDK, Python, JWT, Cognito |
| [aws-multi-account-viewer](https://github.com/kyhau/aws-multi-account-viewer) <br/> My fork of [awslabs/aws-multi-account-viewer](https://github.com/awslabs/aws-multi-account-viewer). | Viewer, React, Python |
| [aws-resource-visualisation](https://github.com/kyhau/aws-resource-visualisation) <br/> Scripts for creating Simple visualisation for some for AWS resources. | CDK, Python, D3 |
| [reko](https://github.com/kyhau/reko) <br/> A simple Python application supporting face based user verification using Amazon Rekognition and Polly, and verbal instructions using Google API speechrecognition. | OpenCV, Polly, Rekognition, Python |
| [aws-capacity-checker](https://github.com/kyhau/aws-capacity-checker) <br/> Simple scripts to retrieve EC2 compute capacity of an AWS account, output results in json and csv files, and display results in html. | Python, html |
| [cdk-examples](https://github.com/kyhau/cdk-examples) <br/> Some AWS CDK (v1 and v2) projects implemented for demo. | CDK, Python |
| [slack-command-app](https://github.com/kyhau/slack-command-app) <br/> A Slack App/Bot that can handle requests triggered from a Slack Command which will take longer than 3 seconds to process, and posts the details back to the user. | Slack-bot, API Gateway, Lambda, Python |
| [aws-cf-templates](https://github.com/kyhau/aws-cf-templates) <br/> My CloudFormation templates | CloudFormation |
| [aws-cognito-angular2-webui](https://github.com/kyhau/aws-cognito-angular2-webui) <br/> My fork of [amazon-archives/aws-cognito-angular-quickstart](https://github.com/amazon-archives/aws-cognito-angular-quickstart). | Cognito, WebUI |
| [reddeer](https://github.com/kyhau/reddeer) <br/> This repo includes some helper scripts and links for performing chaos engineering and red team operations against AWS APIs. | Python |
| [aws-eb-app-template](https://github.com/kyhau/aws-eb-app-template) <br/> Sample repo template for creating ElasticBeanstalk app.| ElasticBeanstalk |
| [hello-visitors](https://github.com/kyhau/hello-visitors) <br/> A simple digital visitor book create with Amazon API Gateway, Lambda, DynamoDB and S3. | API Gateway, Lambda, DynamoDB, S3, Python |
| [chaos-ssm-documents](https://github.com/kyhau/chaos-ssm-documents) <br/> My folk of [adhorn/chaos-ssm-documents](https://github.com/adhorn/chaos-ssm-documents), Collection of AWS SSM Documents to perform Chaos Engineering experiments. | SSM documents, chaos |
| [msk-test-utils](https://github.com/kyhau/msk-test-utils) <br/> MSK utils for testing. | MSK |
| [aws-polly-simple](https://github.com/kyhau/aws-polly-simple) <br/>  Simple code demonstrating how Amazon Polly works. | Polly |
| [warrant](https://github.com/kyhau/warrant) <br/> My folk of [capless/warrant](https://github.com/capless/warrant) - Python library for using AWS Cognito. With support for SRP. | Cognito, Python |


## Data Visualisation and Graphic Source Processing Projects

| Projects | Topics |
| :--- | :--- |
| [simple-webcam-capture](https://github.com/kyhau/simple-webcam-capture) <br/> Python script for capturing an image from a webcam using OpenCV 2. | Webcam, OpenCV 2, Python |
| [GoProStream](https://github.com/kyhau/GoProStream) <br/> My fork of [KonradIT/GoProStream](https://github.com/KonradIT/GoProStream) - Tools for handling/displaying GoPro HTTP/UDP stream (Python/Ruby). | GoPro, Stream |
| [d3-collapsible-tree-demo](https://github.com/kyhau/d3-collapsible-tree-demo) <br/> Example of displaying data in a collapsible tree using D3.js. | D3.js |
| [d3-disjoint-force-directed-graph-demo](https://github.com/kyhau/d3-disjoint-force-directed-graph-demo) <br/> Example of displaying data in a Disjoint Force-Directed Graph using D3.js. | D3.js |
| [d3-icicle-chart-demo](https://github.com/kyhau/d3-icicle-chart-demo) <br/> Example of displaying data in an Icicle Chart (aka Call Tree) using D3.js. | D3.js |
| [d3-indented-tree-demo](https://github.com/kyhau/d3-indented-tree-demo) <br/> Example of displaying data in an indented tree using D3.js. | D3.js |
| [d3-sortable-table-demo](https://github.com/kyhau/d3-sortable-table-demo) <br/> Example of displaying data in a Sortable Table using D3.js. | D3.js |
| [demo_add_bookmark_on_map_with_link](https://github.com/kyhau/demo_add_bookmark_on_map_with_link) <br/> My folk of [w8r/Leaflet.Bookmarks](https://github.com/w8r/Leaflet.Bookmarks) - Demo use Leaflet plugin for user-generated bookmarks. | Leaflet |


## Other Projects

| Projects | Topics |
| :--- | :--- |
| [ssllabs-scan](https://github.com/kyhau/ssllabs-scan) <br/> A simple Python script that calls SSL Labs API to do SSL testings on servers and create a report in html. | Python, ssllabs, html |
| [python-repo-template](https://github.com/kyhau/python-repo-template) <br/> This is a template repository for quickly creating a python application that can be built, tested, and released as an internal python module. | Python |
| [github-workflow-templates](https://github.com/kyhau/github-workflow-templates) <br/> Some workflow examples | GitHub Actions Workflow |
| [phpipam-api-helper](https://github.com/kyhau/phpipam-api-helper) <br/> A simple phpIPAM API helper script finding possible subnets for an IP address. | Python, phpIPAM |
| [panos-api-helper](https://github.com/kyhau/panos-api-helper) <br/> A simple PAN-OS API helper script for finding firewall rule. | Python, PAN-OS |
| [workspace](https://github.com/kyhau/workspace) <br/> Scripts and default configurations for workspace setup automation. | WSL |
| [faq-chatbot](https://github.com/kyhau/faq-chatbot) <br/> A chat bot for answering questions of a topic. | Slack-bot, Python |
| [have-a-smile](https://github.com/kyhau/have-a-smile) <br/> Random Python scripts for fun (getting dilbert, fortune cow, xkcd, etc)  | CDK, Python |
| [codesign](https://github.com/kyhau/codesign) <br/> Create self signed certificates for code signing. | Code signing |
| [google-keep-helper](https://github.com/kyhau/google-keep-helper) <br/> Python scripts for importing bookmarks from Pocket getpocket.com to Google Keep. | Google Keep, Python |
| [gsuite-utils](https://github.com/kyhau/gsuite-utils) <br/> Some scripts for gsuite service automation. | G-Suite, Python |
| [disco_python](https://github.com/kyhau/disco_python) <br/> Docker image of ubuntu 19.04 disco, python 3.7. | Docker Image, Python, disco |
| [bionic_python](https://github.com/kyhau/bionic_python) <br/> Docker image of ubuntu 18.04 bionic, python 3.6, python 3.7 and python 3.8.| Docker Image, Python, bionic |
| [xenial_python](https://github.com/kyhau/xenial_python) <br/> Docker image of ubuntu 16.04 xenial, python 2.7, python 3.6 and python 3.7.| Docker Image, Python, xenial |
| [jessie_python3_node9](https://github.com/kyhau/jessie_python3_node9) <br/> Docker image of jessie, python3.6 and node.js 9.x. | Docker Image, Python, node, jessie |
| [friday-5pm-helper](https://github.com/kyhau/friday-5pm-helper) <br/> Python scripts for pre-filling Replicon timesheet with Jira and Google Calendar data. | Google Calender, Jira, Replicon, Python |
| [nimda](https://github.com/kyhau/nimda) <br/> Admin task helper - simple script for doing what people don't want to do.| Bitbucket, Confluence, Flowdock, Jenkins, Jira, Onboarding, Offboarding |
| [vscode-configs](https://github.com/kyhau/vscode-configs) <br/> My VS Code settings, keybindings and snippets. | vscode |
| [small-coding-exercises](https://github.com/kyhau/small-coding-exercises) <br/> Some small, interesting Python challenges from various sources. | Python |


## Blogs and Notes

| Subject | Topics |
| :--- | :--- |
| [Operational Excellence](https://wa.aws.amazon.com/wat.pillar.operationalExcellence.en.html) | AWS Well-Architected Framework, The Five Pillars of the Framework |
| [aws-notebook/Architecture](https://github.com/kyhau/aws-notebook/blob/master/Architecture.md) | Architecture and Design Patterns |
| [aws-notebook/Security](https://github.com/kyhau/aws-notebook/blob/master/Security.md) | Security related resources and notes |
| [aws-notebook](https://github.com/kyhau/aws-notebook) | My notebook for AWS certification exam preparation |
| [docker-notebook](https://github.com/kyhau/docker-notebook) | My notebook for Docker certification exam preparation |
| [blockchain-notebook](https://github.com/kyhau/blockchain-notebook) | My notes from Blockchain courses |
| [ml-notebook](https://github.com/kyhau/ml-notebook) | My notes from Machine Learning courses |


<!--
**kyhau/kyhau** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
