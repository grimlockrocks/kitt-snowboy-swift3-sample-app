# kitt-snowboy-swift3-sample-app
This is a sample iOS app written in Swift 3 that demonstrates the capabilities of KITT.AI Snowboy

See KITT.AI Snowboy here: https://github.com/Kitt-AI/snowboy

Instructions:
* SnowboyWrapper.h is the Objective-C wrapper for the Snowboy C++ library, which allows Swift 3 code to reference.
* SnowboyWrapper.h does not implement all the methods defined in snowboy-detect.h, only the most important ones, but feel free to add your own.
* ViewController.swift cointains the example usage of Snowboy, which records your voice for 2 seconds and run Snowboy detection. If the result shows 1, then it is a match; 0 means no match; -2 means silent. 
