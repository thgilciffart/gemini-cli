# Gemini CLI 

## Installing the requirements
0. Clone this repository either by running ``git clone https://github.com/thgilciffart/gemini-cli.git`` or by clicking on Code and download zip and extract the files to a directory
1. Ensure you have [Node-js](https://nodejs.org/en/download) version 20 or higher installed. 
2. Download Gemini Cli 
```
npm install -g @google/gemini-cli
```
3. Follow through the Gemini setup process by using the command anywhere
```
gemini
```
For further reading on gemini cli check out the [Github](https://github.com/google-gemini/gemini-cli).

## Usage
- Use prompts such as this
```
EXPLAIN -- QUESTION/CONCEPT
```
```
SOLVE -- QUESTION 
```

### Using it from anywhere
CDing into the subject directory can be annoying so add this to your user PATH.
1. Search SystemPropertiesAdvanced
2. Click on the Advanced tab
3. Click on Environment Variables
4. Select PATH
5. Press edit
6. Press new and browse and select this directory.

Now you want to create a batch file within this directory that will change directory into the folders then run Gemini
Here is an example ``math.bat``
```
@echo off
cd %userprofile%\Documents\gemini-cli\Math
gemini 
```
![Example](/Images/example.png)