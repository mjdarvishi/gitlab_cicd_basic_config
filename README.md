# Gitlab cicd configuration

This is a basic gitlab cicd pip line configuration which you can use and customize.
It has 6 stages:
* build
*  test
*  lint
*  push
*  new_release
*  deploy

## Features:
* diffrent deployment approach. you can use diffrent runner in diffrent machin with diffrent kind of tag for deploying your code in diffrent kind of envirment like development, production and .....
* create release by using git tag
* you can add linting check after and before merge request
* impliment diffrent aprach for building your app base on you code structure in build stage.

This code is just a template and you have to impliment each stage by your self. you can use this template for diffrent kind of pip line for diffrent platforms.
