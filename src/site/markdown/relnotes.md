# Release Notes OGC WMS 1.1.1 Test Suite

## 1.20 (2020-12-15)
   * [#58](https://github.com/opengeospatial/ets-wms11/issues/58) - Improve organisation of tests
   * [#59](https://github.com/opengeospatial/ets-wms11/issues/59) - Improve documentation

## 1.19 (2019-08-19)
   * [#68](https://github.com/opengeospatial/ets-wms11/pull/68) - Fixed Fortify Issues for DISASTIG
   * [#72](https://github.com/opengeospatial/ets-wms11/issues/72) - REST API: URI of test suite is equal to WMS 1.3 test suite
   * [#71](https://github.com/opengeospatial/ets-wms11/issues/71) - Update tests to use TEAM Engine 5.4
   * [#62](https://github.com/opengeospatial/ets-wms11/issues/62) - Create SoapUI tests and integrate them into Maven and Jenkinsfile
   * [#69](https://github.com/opengeospatial/ets-wms11/issues/69) - Test error "Error: A sequence of more than one item is not allowed as the first argument of contains()"

## 1.18 (2018-08-28)
   * [#63](https://github.com/opengeospatial/ets-wms11/issues/63) - Test wms:wmsops-getmap-params-exceptions-4 fails if format with parameter is used in request
   * [#60](https://github.com/opengeospatial/ets-wms11/issues/60) - Test wms:wmsops-getcapabilities-params-request-1 uses wrong request parameter value

## 1.17 (2018-05-16)
   * [#53](https://github.com/opengeospatial/ets-wms11/issues/53) - Update CTL with better information about conformance classes

## 1.16 (2017-08-22)
   * [#52](https://github.com/opengeospatial/ets-wms11/issues/52) - No Rest API
   * [#54](https://github.com/opengeospatial/ets-wms11/issues/54) - Problem with WMS 1.1.1 validation (wms:wmsops-getmap-each-srs fails due to XSLT failure)

## 1.15 (2017-01-31)
   * [#50](https://github.com/opengeospatial/ets-wms11/issues/50) - missing urlencoding

## 1.14 (2016-04-29)
   * [#47](https://github.com/opengeospatial/ets-wms11/issues/47) - value of INFO_FORMAT parameter not URL-encoded

## 1.13 (2016-02-23)
   * [#43](https://github.com/opengeospatial/ets-wms11/issues/43) - Empty SRS - wmsops-getmap-each-layer

## 1.12 (2015-11-30)
   * [#40](https://github.com/opengeospatial/ets-wms11/issues/40) - wms:wmsops-getmap-params-exceptions-6 fails for gif images with indexed tranparency

## 1.11 (2015-10-27)
   * [#39](https://github.com/opengeospatial/ets-wms11/issues/39) - wmsops-getmap-each-srs does not handle AUTO correctly
   * [#35](https://github.com/opengeospatial/ets-wms11/issues/35) - Documentation problems for WMS 1.1.1

## 1.10 (2015-06-10)

   * [#32](https://api.github.com/repos/opengeospatial/ets-wms11/issues/32) - wms:wmsops-getmap-each-style
   * [#30](https://api.github.com/repos/opengeospatial/ets-wms11/issues/30) - Incorrect failing for Transparency due to PNG
   * [#24](https://api.github.com/repos/opengeospatial/ets-wms11/issues/24) - GFI tests executed without choosing GFI for testing
   * [#23](https://api.github.com/repos/opengeospatial/ets-wms11/issues/23) - wmsops-getfeatureinfo-params-query_layers-3 and wmsops-

## 1.9 (2015-03-26)
  
  * [#13](https://github.com/opengeospatial/ets-wms11/issues/13) - A WMS can now pass if properly implemented the OLD DTD or the new DTD.

## 1.8 (2015-02-20)
All the log at [Github](https://github.com/opengeospatial/ets-wms11/issues?q=milestone%3A1.8). Noteworthy:

  * [#12](https://github.com/opengeospatial/ets-wms11/pull/12) - Remove normalize-string, substring-before; Replaced with contain
  * [#9](https://github.com/opengeospatial/ets-wms11/pull/9)- Fix for issue LayerNotDefined - Assertion #5  
  * [#6](https://github.com/opengeospatial/ets-wms11/issues/6)- Adjust configuration
  * [#10](https://github.com/opengeospatial/ets-wms11/pull/10)- Fix issues with reference implementations
  * [#20](https://github.com/opengeospatial/ets-wms11/issues/20) - Verifying transparency of PNG image
  * Starting this revision, the revision number will follow the conventions described in the [wiki](https://github.com/opengeospatial/cite/wiki/OGC-Compliance-Testing-Tools)

## r7 (2014-06-24)
  * [#5](https://github.com/opengeospatial/ets-wms11/issues/5) - LayerNotDefined - Assertion #5 - added HTTPParser to wmsops-getmap-params-layers-6 test

## r6 (2014-06-20)

  * [#4](https://github.com/opengeospatial/ets-wms11/issues/4) - Fixed CITE-943: (GetFeatureInfo) Tests fail but the response seems valid - wms:basic_elements-param_rules-order_and_case-5
  * [#6](https://github.com/opengeospatial/ets-wms11/issues/1) - Fixed CITE-828: Broken SRS parameter in some tests: In functions:layer-info, look for preferred SRS ("EPSG:4326") if given.

## r5 (2013-12-10)
  * Fixed CITE-913: Image parser for wms:wmsops-getmap-params-exceptions-5 and wms:wmsops-getmap-params-exceptions-6

## r4 (2013-12-03)
  * Fixed CITE-892: Invalid requests
  * Fixed CITE-891: Color and alpha tests fail
  * Fixed CITE-886: DTD does not match
  * Fixed CITE-828: Broken SRS parameter in some tests
  * Fixed CITE-904: Invalid layer/style combinations

## r3 (2013-02-09)
  * Updated config.xml for TEAM-Engine v4
  * Fixed several XPath errors: "A sequence of more than one item is not allowed as the first argument of string() (<Name/>, <Name/>, ...)" -> select first match.
  * Added note about required libraries

## r2 (2010-11-15)
  * updated release notes. 2010-11-15 (kstegemoller):
  * updated "Latest" release notes.2010-08-27 (kstegemoller):
  * fixed documentation typo. 2010-08-25 (aschmitz):
  * changed transparent value to FALSE as suggested in issue #25. 2010-07-05 (aschmitz):

## r1 (2009-10-12)
  * Created revision tag wms-1.1.1 r1. 2009-10-12 (kstegemoller):

## r0 (2009-10-7) cmorris
  * Fixed tests that did not include a Version parameter (Issue 309)
  * Added tests written for NSG that apply to the base WMS specification: 
    1. When a layer is requested using escaped characters in its name, the response is a map
    2. When an exception is generated, it validates
    3. For each format a request with TRANSPARENT=TRUE does not return an exception.
    4. For each image format advertised in capabilities, When a GetMap request is made using the image format, then the Content-type entity header returned is the format requested.
    5. For each SRS in the capabilities document, when a GetMap request uses the SRS, then the response is valid.
    6. For each of the Layers in the capabilities document, when a GetMap request is made with the LAYERS parameter set to the element of the layer, then the response is valid.
    7. For each of the Styles in the capabilities document, when a GetMap request is made with the STYLES parameter set to the element of the style, then the response is valid.
    8. For each advertised GetFeatureInfo format, when a GetFeatureInfo request is made with the INFO_FORMAT parameter set to the format, then the Content-type header returned is the same.
