# Komodo Joomla Builder
## Description
Create a Joomla file structure using Komodo and Grunt 
This project is based on Komodo's Extension Generator where it would create a project file in a project directory and then populate the directory with Komodo's extension file structure with prompts to the user to input information for extension details and creating a manifest file with accompanying macros to modify the manifest file, build the extension and build and install the extension to Komodo.

## Project Scope
With this project it will do a similar procedure in combination with GruntJS, plugins and Komodo macros to create the Joomla infrastructure, with the ability to modify and add Joomla files and functions, do syntax checks, ensure compliance with Joomla coding standards, use autocomplete for Joomla coding.

## What is Joomla?
Joomla is an award-winning content management system (CMS), which enables you to build Web sites and powerful online applications. Many aspects, including its ease-of-use and extensibility, have made Joomla the most popular Web site software available. Best of all, Joomla is an open source solution that is freely available to everyone.
More information can be found [here](http://www.joomla.org/)

## What are the parts of Joomla

### Component

### Plugin

### Templates

## Workflow 
## Download Komodo Joomla Builder
After downloading and installing the Komodo Joomla builder file (Work In Progress (WIP))

## Joomla naming convention
Joomla requires that the naming convention of files and functions be consistent throughout the project to utilise the Joomla infrastructure.

### Building Joomla component procedure
The first time the developer uses the builder they are prompted for default parameters.
Such as author name, email, url etc this information is stored in a config file for later reference.
It then displays a project help information outlying the workflow.

It does a check for global nodejs installation and prompts if not installed as this is required for grunt
then checks for global grunt installation and prompts if not installed.

## Macros and their function
### Komodo Extension - Create Joomla Project
create the project, add macros to Joomla project, modify default user data, modify default parameters for grunt and plugins, add plugins to list, help on using builder

## Joomla Project Macros
## Create Project
User selects create project macro
User selects type a component, plugin or template
default parameters are read and displayed
user adds additional information
user selects project directory

the builder checks for local nodejs 
checks for local grunt
user selects grunt plugins to install
list standard plugins
allow user to add custom plugins
Gruntfile.js created with standard parameters
package.json created with standard parameters

project name is built with Joomla file infrastructure and files
creates projectname manifest file

### after project is created

options to modify parameters of plugins
modify package.json

user types in joomla specific code
intelisense / autocomplete
For example if label is added ie MYPROJECT.THISISDESCRIPTION the builder then adds label data and prompts user to add text to the language file.
