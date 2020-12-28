# A-S-IOS-Shopfloor

An IOS Shortcuts-based tool to enter start and stop times against an Avanti Slingshot job.

## Goals

Allow for a single user shop floor data collection client that minimizes keying and allows for realtime collection of labor expended against a production job

## Requirements

* iPhone or iPad with iOS 14 or greater set to not autolock the screen
* Avanti Slingshot (Self-hosted or Cloud deployment both OK)
* Single JDF connection license or JDF Framework license

## Basic Usage

When starting a job the user scans a barcode for the job number off of a job ticket or a screen, which will be used to communicate back to Avanti Slingshot. They will then be asked which section they are working on.  While production activities are running, the shortcut will wait for confirmation of the completed task, and then send Avanti Slingshot a JMF signal with the task completed, and the time spent on the task.

## Advanced Scenarios

* Using a NFC tag to trigger the correct shortcut based upon the task/equipment being worked on.
