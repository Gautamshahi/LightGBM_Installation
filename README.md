# LightGBM_Installation
In this repository the basic step of installation of LightGbm in Windows is mentioned.
In this turotial i am mentioning the steps to intall the Lightgbm using Visual Studio.

For Image view of each step, refer to Image Folder
Step 1- Download the LightGBM framework from https://github.com/Microsoft/LightGBM
Step 2- Install Visual Studio Installer from https://www.visualstudio.com/3c1eaa29-56ff-4af0-8386-94c8fae7e925
Step 3- Install Visual Studio 2017 suing the Installer
Step 4- Install the Dependencies Like from the Visual Studio Installer--Individual Components
Step 5- Open the Solution File in Visual Studio from your local directory example- E:\LightGBM-master\LightGBM-master\windows
Step 6- Change the solution configuration to Release
Step 7 - Build the project
Step 8- Copy the Lightgbm.exe file from E:\LightGBM-master\LightGBM-master\windows\x64\Release to the the example forlder 
Stepl 9- I wnats to run the Regression examples so i copy the lightgbm.exe in Regression Folder in the link E:\LightGBM-master\LightGBM-master\examples\regression
Step -10 Open cmd and go to the Lightgbm' Regression Example
Step - 11 For Training lightgbm.exe config=train.conf
          For Prediction ./lightgbm config=train.conf
Step- 12 Now elaborate all examples and try to understand the code
Step 13- run your data similarly


