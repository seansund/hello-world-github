# SpringBoot project template

This project provides a template to quickly start a new SpringBoot project that comes pre-configured
with a number of useful features. It is intended to be customizable, extensible, and to be updated as
the underlying template is updated.

## Getting started

### Create the project

#### Clone the project

To get started clone this repo into a local folder, preferably one with a different name:

```bash
git clone --single-branch {url} {new_name}
```

**OR**

#### Create the toolchain

Create the toolchain and clone the project into a GitHub repository by clicking on the button

[![Deploy To Bluemix](https://console.ng.bluemix.net/devops/graphics/create_toolchain_button.png)](https://console.ng.bluemix.net/devops/setup/deploy/?repository=https://github.ibm.com/seansund/template-spring-boot&repository_token=615201574e514665d9f8e570cdb77a5d6a1f0258&branch=toolchain_github)


### Set up the project from the template

Next, run the `setup-template.sh` script. It will ask for you project name and the url to your new 
repo. If no project name is provided the script will default to using the folder into which the repo 
was checked out.

```bash
./setup-template.sh
```

### Periodically update from the template

Finally, the template components can be periodically updated by running the following:

```bash
./update-template.sh
```

## More information

Once the `setup-template.sh` script has been run, this README.md file will be replaced with a new 
file for the project. More information about the template features and how they are used can be 
found in [TEMPLATE.md](TEMPLATE.md)