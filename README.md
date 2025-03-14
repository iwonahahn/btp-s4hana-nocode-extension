[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/btp-s4hana-nocode-extension)](https://api.reuse.software/info/github.com/SAP-samples/btp-s4hana-nocode-extension)
# Side-by-side UI Extensions on SAP BTP Using SAP AppGyver

The main focus of this mission is to develop a custom UI application, which consumes an OData service from an SAP S/4HANA Cloud system.

We will create a simple custom UI application using no-code tool **SAP AppGyver**, push the code to the HTML5 repository and show different options on how to expose this application - as a stand-alone or with the different SAP Launchpads environments.

## Business Scenario

As a sample scenario, Jane a sales executive of ACME Corporation regularly meets different customers. She needs access to latest customer information on the go. She needs a simplified web application, which can run on a portable device like smartphone or a tablet.

ACME Corporation implements the application as an SAP S/4HANA Cloud extension on SAP Business Technology Platform (SAP BTP). This application is created with SAP AppGyver, a no-code user interface development tool.

This scenario covers:

* Building application with SAP AppGyver
* Set up connectivity between SAP BTP and SAP S/4HANA Cloud
* Deploying the application on SAP BTP, Cloud Foundry environment

## Solution Architecture

 ![Solution Architecture](./discover/images/ScenarioArchitecture.png)

## Discover

* [The Mission Story](discover/business-story.md)
* [Learn the Basics of SAP BTP](https://github.com/SAP-samples/cloud-extension-html5-sample/blob/mission/mission/discover/BTP.md)
* [Learn about SAP S/4HANA](https://github.com/SAP-samples/cloud-extension-html5-sample/blob/mission/mission/discover/S4H.md)
* [Learn about SAP S/4HANA Cloud](./discover/S4HC.md)
* [Learn about HTML5 Applications](https://github.com/SAP-samples/cloud-extension-html5-sample/blob/mission/mission/discover/HTML5.md)
* [Learn about SAP AppGyver](./discover/AppGyver.md)
* [Learn about SAP Cloud Identity Services](https://github.com/SAP-samples/cloud-extension-html5-sample/blob/mission/mission/discover/IAS.md)
* [Learn about SAP Launchpad Service and SAP Work Zone](https://github.com/SAP-samples/cloud-extension-html5-sample/blob/mission/mission/discover/Launchpad.md)



## Landscape Setup for SAP BTP and SAP S/4HANA Cloud

  - [Subscribe to the Low-Code / No-Code Service in SAP BTP](./setup/btp/README.md)
  - [Subscribe to SAP Launchpad Service](./setup/launchpad/README.md)
  - [Onboard SAP S/4HANA Cloud System](./setup/s4hc-onboarding/README.md)
  - [Configure Communication Settings in SAP S/4HANA Cloud](./setup/s4hc-setup/setup-s4hc-system.md)
  - [Configure End-to-End Connectivity from SAP BTP to SAP S/4HANA Cloud System](./connectivity/end-to-end-connection.md)
  - [Configure Single Sign-On between SAP S/4HANA Cloud and SAP BTP](https://github.com/SAP-samples/cloud-extension-html5-sample/blob/mission/mission/custom-idp/README.md)
  - [Map SAP BTP Role Collections to Identity Authentication Service Users](./setup/rolemapping/README.md)


## Landscape Setup for SAP BTP and Mock Server

If you don't have an SAP S/4HANA system, you can use a mock server setup instead.

  - [Subscribe to the Low-Code / No-Code Service in SAP BTP](./setup/btp/README.md)
  - [Subscribe to SAP Launchpad Service](./setup/launchpad/README.md)
  - [Install Mock Server](./setup/mock/README.md)


## Implementation of an SAP AppGyver Extension Application

Once you have set up the landscape, you can develop, test, and run a simple UI application. We will show the steps to implement the simple UI application using the SAP BTP-managed HTML5 repository. This is a kind of PoC to see if and how the whole landscape setup is working.

* Develop a simple UI application:
  * [Create Base Application](./create-application/develop/README.md)
  * [Create List Page](./create-application/develop/ListPage/README.md)
  * [Create Details Page](./create-application/develop/DetailsPage/README.md)
  * [Build and Deploy the Application to your SAP BTP Cloud Foundry Account](./create-application/deploy/README.md)

## How to obtain support
[Create an issue](https://github.com/SAP-samples/btp-s4hana-nocode-extension/issues) in this repository if you find a bug or have questions about the content.
 
For additional support, [ask a question in SAP Community](https://answers.sap.com/questions/ask.html).

## Contributing
If you wish to contribute code, offer fixes or improvements, please send a pull request. Due to legal reasons, contributors will be asked to accept a DCO when they create the first pull request to this project. This happens in an automated fashion during the submission process. SAP uses [the standard DCO text of the Linux Foundation](https://developercertificate.org/).

## License
Copyright (c) 2022 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSE) file.
