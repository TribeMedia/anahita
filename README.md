![Anahita social networking platform and framework](https://s3.amazonaws.com/anahitapolis.com/media/logos/homepage_logo.png)

# Anahita

*Version:* 4.1.0 Embryo Release

Anahita is a remarkable social networking platform for developing knowledge sharing apps and services. Use Anahita to launch:

1. online learning and knowledge sharing networks
2. information access networks about people, places, and things
3. open science and open data
4. online collaboration
5. cloud back-end for your mobile apps

Anahita provides a genuine nodes and graphs architecture as well as design patterns for building apps that are smarter and inherently social.

## Features

### Nodes
1. *actors:* people, groups, or build your own custom actor
2. *media:* notes, topics, todos, photos, pages, or build your own custom media
3. *hashtags:* all actors, media, and comments are hashtagable  
4. *stories:* updates created by actors for their followers

### Graphs
1. *social graph:* people and groups can be followed by other people. 
2. *hashtags:* for actors, media, and comments
3. *mentions:* tag people in media and comments
4. *notifications:* a person recieves an email notification whenever a comment is posted on an item they are subscribed to.
5. *votes:* people can Like/Unlike media and comments

### Stories
- story feeds on dashboard and actor profiles
- notifications

### More Features
1. *media composer:* for posting notes, topics, pages, todos, and photos from actor profiles or the dashboard.
2. *commnets:* all media are commentable 
3. *privacy management:* for actors and media nodes
4. fully customizable theme and user interfaces
5. extendable by social apps and components
6. specialized Anahita framework to build your own custom social apps
7. RESTful and JSON APIs (ideal to use Anahita as a back-end for mobile apps)

### Built using your favourite technologies
PHP, MySql, Bootstrap, JQuery, Grunt, Composer, LessCSS

## Installation

Before you start please make sure that your server meets the following requirements:

1. Linux or unix server
2. Apache 2.0+ (with mod_mysql, mod_xml, mod_zlib) or Nginx
3. MySql 5.0+
4. php 5.3.3+ with APC
5. Composer package management. You can download it following the instructions on
http://getcomposer.org/ or just run the following command:

`curl -s http://getcomposer.org/installer | php`

#### Important Notes

1. If you have the suhosin patch installed on your server you might get an error. Add this line to your php.ini file to fix it: `suhosin.executor.include.whitelist = tmpl://, file://`
2. If you have Zend Optimizer on your server *disable it*!
3. Anahita is installed and managed via commandline, becuase this is the most reliable approach especially after you accumulate large amounts of data in your database.

### System Requirements

### Installing a Birth Release

### Installaing an Embryo Release

## Configuration

### Installing Social Apps

### Amazon S3 Storage

## Anahita Cli

## Report Bugs or Issues

## Contribute to Anahita

Getting Started
================
To install the most recent Birth release of Anahita please read the instructions [Getting Started] (https://github.com/anahitasocial/anahita/wiki/Getting-started).

Get Help
=========
If you need any help with the Anahita installation or have general question about Anahita. 
You visit http://GetAnahita.com or follow the Anahita project group at http://www.GetAnahita.com/groups/group/42242-anahita
