# CodeBugFixer_AI_Application
To develop this SaaS application, we will be utilizing a tool that you may already be well acquainted 
with, namely, the Flask framework for building web applications in Python. Our aim is to become 
proficient in utilizing this framework to build an effective and scalable web application that can deliver 
efficient code error solutions to its users.

In this Application, we will Perfrom certian operations:
*  Building a code bug-fixing SaaS application using Flask.
* Using the ChatGPT API to generate explanations and solutions to code errors.
*  Creating a web form that accepts user input for code and error messages
*  Designing a web interface to display the generated explanations and solutions.
*  eploying an application to the Azure cloud platform.
*  Integrating an application with a WordPress website.


## Technical Requirements
The technical requirements for this project are as follows:
*  Python 3.7 or later installed on your machine.
* A code editor, such as PyCharm (recommended).
* A Python virtual environment.
* The Flask web framework installed in the virtual environment
* Access to Microsoft Azure.

The design of the user interface is simple and intuitive, with two text areas for code and error input, 
and two read-only text areas for displaying the generated explanation and fixed code. The app’s layout 
is clean, with a blue and white color scheme and a centered header that displays the app’s name. The 
app is designed to provide a seamless user experience for identifying and fixing code errors.

![IMG_20231206_120800](https://github.com/gurpreetsingh1111/CodeBugFixer_AI_Application/assets/84591513/24e059e5-f7ae-4af5-8625-3f5478d7096b)

## The project structure should look like the following:
* CodeBugFixer/
 > ├── config.py
>  ├── app.py
>  ├── templates/
>  │ └── index.html

## Testing the Code Bug Fixer App
* Now, we will learn how to test our Code Bug Fixer application. We will write some test cases to ensure 
that the application is functioning correctly and handling different scenarios appropriately. Testing 
is a critical part of software development, as it ensures that the application works as intended and 
meets the user’s requirements.
* The Code Bug Fixer app can fix any programming language, making it a versatile tool. Therefore, we 
will demonstrate its effectiveness by using examples written in two different programming languages: 
Java and Python

![IMG_20231206_120740](https://github.com/gurpreetsingh1111/CodeBugFixer_AI_Application/assets/84591513/b281a8fc-4cd4-43c8-ac47-af8c3692e9be)

## Deploying the ChatGPT App to the Azure Cloud
 upload our Code Bug Fixer application to the Azure cloud platform. Azure is a cloud computing 
service provided by Microsoft that allows developers to host, manage, and scale their applications in 
the cloud. By hosting our application on Azure, we can make our application accessible to a wider 
audience. We will go through the steps required to create an Azure account, set up our application 
for deployment, and deploy it to Azure using the Azure CLI.

* 1. Open your macOS Terminal.
* 2. Install brew. Homebrew is a popular package manager for macOS:
> $ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
* 3. Once Homebrew is installed, run the following command to install Azure CLI:
> $ brew update && brew install azure-cli
* 4. Verify that the installation was successful by running the following command:
> $ az --version
* 5. This should display the version number of the Azure CLI that you just installed:
-- azure-cli 2.47.0
-- core 2.47.0
-- telemetry 1.0.8
-- Dependencies:
-- msal 1.20.0
-- azure-mgmt-resource 22.0.0
> Python location '/opt/homebrew/Cellar/azure-cli/2.47.0/libexec/bin/python'
> Extensions directory '/Users/martinyanev/.azure/cliextensions'
> Python (Darwin) 3.10.11 (main, Nov 28 2023, 07:24:47) [Clang 14.0.0 (clang-1400.0.29.202)]
> Legal docs and information: aka.ms/AzureCliLegal
> Your CLI is up-to-date


