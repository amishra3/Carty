![Cognifide logo](http://cognifide.com/~/media/wireframe/int/images/cognifide_logo.png)
 
![Carty logo](http://cognifide.github.io/Carty/assets/media/logo-carty.png)

## Purpose

Carty is an integrated tool to create, edit, review and test Sling mappings for Adobe CQ/AEM. [Read more](http://cognifide.github.io/Carty/).

## Features
 
* mapping generator - enter domain and the content path and Carty will take of everything else,
* mapping editor - edit, move, create and delete sling:Mapping entries,
* tester - check what will be the result of the map or resolve operation,
* highlighter - Carty explains which entries have been applied to a specific part of the tested URL,
* configuration - you may choose any path to create mappings, it doesn't have to be the mapping root currently set in the Resource Resolver
 
## Prerequisites
 
* CQ 5.6.1 or higher
* Maven 3.x
 
## Installation
 
    mvn clean install crx:install

Optionally, you may set Maven properties: `instance.url`, `instance.login` and `instance.password`.

## Usage
 
Find Carty under the `/miscadmin`.

## Screenshot

<img src="http://cognifide.github.io/Carty/assets/media/carty-screenshot.png" height="300"/>
