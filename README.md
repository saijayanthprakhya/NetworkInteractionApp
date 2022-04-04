# NetworkInteractionApp
This web application is a simple interaction program that users can call using REST API calls. The application interacts with the Network Devices based on the user inputs and provides respective outputs.
It is based on Python3 and Flask microframework.

Problem Statement:
1. Create a Git repository (on GitHub or GitLab) and share the URL with us.
2. Setup a network device(s) for your program to interact with (your program is expected to interact with this device during the demo). We have a preference for an emulated device however a physical device will be ok as well. You will need to interact with this device via netconf and cli.
3. Write a program in python that listens for REST/CLI calls and interacts with a network device.
User -----HTTP/REST/CLI----> [Your Automation Program] ---Netconf/Cli-----> Device
You can chose the framework of your liking (flask, django, ROBOT etc).

Solution proposed:

Choices of tools/frameworks/languages etc used for the project:

1. The usecase for this application is for an end user who can provide his inputs via REST API calls. The user may use curl/Postman etc for calling the REST APIs.
2. The Application consumes the API requests and based on the inputs in the body of the API call, it interacts with the Network Device. The Application is developed using Python3 and Flask microframework for API consumption; Python's netmiko module is used for Application's interaction with the Network Device.
3. The choice of network devices for this project is GNS3 at this moment.

TLDR!
