# OGC Web Map Service 1.1.1 Test-Suite

The OGC Web Map Service Test-Suite provides the Executable Test Script (ETS) to test implementations against the following specification(s):

  * _Web Map Server Implementation Specification_, version 1.1.1 [OGC 01-068r3](http://portal.opengeospatial.org/files/?artifact_id=1081&version=1&format=pdf)

Detailed information about this test suite is available [here]( http://opengeospatial.github.io/ets-wms11/).

## License

[Apache 2.0 License](LICENSE.md)

## Building

This test is build using [Apache Maven](http://maven.apache.org/). To 
build the test suite run maven from the root directory.
```
   % mvn install
```   

Follow the [TEAM ENGINE instructions] (http://opengeospatial.github.io/teamengine/installation.html) to install and run the tests in TEAM ENGINE.     
 
## How to run the tests

#### 1. Docker

This test suite comes with a Dockerfile which can be used to easily setup the OGC test harness with
the test suite. Details can be found on [Create Docker Image and create and start Docker Container](https://github.com/opengeospatial/cite/wiki/How-to-create-Docker-Images-of-test-suites#create-docker-image-and-create-and-start-docker-container).

#### 2. OGC test harness

Use [TEAM Engine](https://github.com/opengeospatial/teamengine), the official OGC test harness.
The latest test suite release are usually available at the [beta testing facility](http://cite.opengeospatial.org/te2/). 
You can also [build and deploy](https://github.com/opengeospatial/teamengine) the test 
harness yourself and use a local installation.


## Bugs

Issue tracker is available at [GitHub](https://github.com/opengeospatial/ets-wms11/issues).

## Mailing Lists

The [CITE Forum](http://cite.opengeospatial.org/forum) is where software developers discuss issues and solutions related to OGC tests. 

## More Information

Visit the [CITE website](http://cite.opengeospatial.org/) to get more information about the CITE program and tools.
