<h1 align="center">
  <br>
  <a href="StatiCAN"><img src="https://github.com/Mgharbieh/StatiCAN/blob/main/ui/assets/statiCAN.png" alt="StatiCAN" width="1250"></a>
  <br>
</h1>

<h4 align="center">Open source tool for CAN implementation error detection and correction.</h4>

<p align="center">
  <a href="#key-features">Key Features</a> •
    <a href="#setup-instructions">Setup Instructions</a> •
  <a href="#how-to-use">How to Use</a> 
</p>

## Key Features
* Find issues in CAN protocol implementation for Arduino-based projects
* Simple explanations for nontechnical users
* Code highlighting to emphasize problematic lines of code
* AI-powered solutions to fix detected issues
* Fully optional AI usage:
  - Completely disable all AI features without impacting issue detection
  - AI model customization to better fit to users' preferences
  - No API key required for select models*

 *No key required for use with Llama3.  Other models require valid API keys to work.

## Setup Instructions
1) [Download Ollama](https://ollama.com/download)
2) Once installed open a terminal and run the following: <br> ``` ollama pull llama3 ``` </br>
3) Wait for download to complete
4) Download StatiCAN from [Releases](https://github.com/Mgharbieh/StatiCAN/releases)
5) Run StatiCAN to launch the program.  By default, AI features are turned off.  Select Llama3 in settings to enable AI features without any API keys or rate limits.

## How to Use
* Select the '+' icon to upload an Arduino sketch (.ino file)
* A card will appear on the pane to the right.  Wait for the file to finish being scanned.
* Select the card to view potential issues.  By default, AI suggestions are turned off.  This can be changed in settings.
* If AI solutions are enabled, select an issue from the right pane to generate a potential fix for the solution. Problematic lines of code are visible on the source code pane to the left.

## 
  <br>
  <a href="umdcecs"><img src="https://umdearborn.edu/sites/default/files/styles/header_logo/public/2021-06/cecs.png?itok=Ycf4lAOi" alt="UM Dearborn CECS" width="1250"></a>
  </br>
  
## 
