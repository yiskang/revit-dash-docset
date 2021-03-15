# Autodesk Revit API Dash DocSet

## Description

Autodesk Revit API Dash DocSet convert from CHM file inside Revit SDK.

## How to build your own DocSet

### Requirements

- PHP version 5.4.0 and above.
- Use [Composer](http://getcomposer.org/) to install package dependencies.
- Use [Dash](http://kapeli.com/) app to open the generated DocSet.

### Usage

1. Download Revit SDK installer from https://www.autodesk.com/developer-network/platform-technologies/revit
2. Install Revit SDK to your Windows machine
3. Clone this repo: git clone https://github.com/yiskang/revit-dash-gen
4. Extract `RevitAPI.chm` from the SDK installation folder
5. Copy `RevitAPI.chm` to the root folder of this project aside to the index.php
6. Install dependencies, so run `composer install` in your terminal
7. Run this project
    ```
    php index.php --out=./test/adsk-revit-api.docset --id='adsk-revit' --name='Autodesk Revit' ./RevitAPI-2021-1.chm
    ```
8. Double clicking on `adsk-revit-api.docset` to open the DocSet.

## Bug report and DocSet improvement

Best is to drop an issue or do a PR at the Docset's repo: https://github.com/yiskang/revit-dash-gen

## Author

Eason Kang [@yiskang](https://twitter.com/yiskang), [Autodesk Forge Partner Development](http://forge.autodesk.com)