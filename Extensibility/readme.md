# Cisco Crosswork Network Controller 4.1 Service Extensibility SDK

This repository contains the 4.1 version of the Cisco Crosswork Network Controller (CNC) Service Extensibility SDK. The code, APIs, and examples in this SDK are designed to help you get started customizing default CNC service provisioning and visualization behavior to meet the needs of your organization.

## Requirements

To use this version of the SDK, you will need:

- Cisco Crosswork Network Controller 4.1
- Java JDK 11
- Python 3.8+ (if you will use the SDK with Python code)
  
## Setup

You must set up the environment before attempting development or building the examples. Here are the steps to follow to set up the environment:

1.  Install Python 3.8 and Java JDK 11 (One-Time Setup)
    If you would like to use the SDK with Python, Python 3.8 or above is required (|you can download Python here|(<https://www.python.org/downloads/>)). JDK 11 is the required version, and may already be installed (|you can download the JDK here|(<https://aws.amazon.com/corretto/>)).

    After installing the JDK, make sure you have the JAVA_HOME environment variable set and exported, as follows:

    ```shell
    echo $JAVA\_HOME`
    ```

    If the JAVA_HOME variable is not set, set it using the export command. For example:

    ```shell
    export JAVA\_HOME=/Library/Java/JavaVirtualMachines/amazon-corretto-11.jdk/Contents/Home`
    ```

2. Clone the SDK repository
    How do they do this? Or are we going to distribute it as a ZIP package?

3. Generate the sdkrc file.  
    The sdkrc file is a shell script  that sets the SDK environment. Go to the SDK root folder ( the home directory for the SDK), and then run the setup script from the bin directory. For example: 

     ```shell
    cd tsdn-fp-sdk
    ./bin/setup
    ```

4. Run the Setup Script
    This step is required to set up the development environment so that it can use the tools provided in the SDK:

    ```shell
    source ./sdkrc
    ```

    This is the first step you perform on any new shell or terminal window. You can add it to your bash profile, so that it will run every time you open a shell or terminal window.
