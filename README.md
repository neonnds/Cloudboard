# Cloudboard
A private cloud that contains all your files using total.js and elastic-search.

## Releases

* [Version 2015.04](https://github.com/neonnds/Cloudboard/cloudboard-2015-04.tar.gz)

## Todo

* Complete Information Panel
* Allow for bulk tagging of uploads
* Allow for pause and resume of individual uploads
* Allow set public flag on uploads
* Add advance search options
* Add input validation

## Getting Started

Get Cloudboard

    $> wget https://github.com/neonnds/Cloudboard/cloudboard-2015-04.tar.gz
    
Extract Cloudboard

    $> tar -zxf cloudboard-2015-04.tar.gz
    
Enter the Cloudboard project

    $> cd ./Cloudboard

Get ElasticSearch from the offical site

    $> wget https://download.elasticsearch.org/elasticsearch/elasticsearch/elasticsearch-1.5.0.tar.gz
    
Extract ElasticSearch

    $> tar -zxf elasticsearch-1.5.0.tar.gz
    
Start Elastic Search

    $> ./elasticsearch-1.5.0/bin/elasticsearch

Start Cloudboard

    $> nodejs index.js


## Development

### Requirements

* [Elastic-Core](https://github.com/neonnds/Elastic-Core)

* [CUID](https://github.com/ericelliott/cuid)

* [GM](https://github.com/aheckmann/gm)

* [async](https://github.com/caolan/async) 

### Linux Installation

Enter the Elastic-Core project sites directory

    $> cd ./Elastic-Core/sites

Get the Cloudboard project

    $> git clone https://github.com/neonnds/Cloudboard.git

Enter the Cloudboard project

    $> cd ./Cloudboard

Install the following node modules

    $> npm install bcrypt-nodejs --save
    
    $> npm install cuid --save
    
    $> npm install gm --save
    
    $> npm install async --save

Enter the Elastic-Core project

    $> cd ./Elastic-Core

Start Elastic Search

    $> ./elasticsearch-1.5.0/bin/elasticsearch

Start Cloudboard

    $> ./run Cloudboard
