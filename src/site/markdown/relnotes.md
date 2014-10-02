# Release Notes OGC WMS 1.1.1 Test Suite

## r8 (2014-10-XX)
  * [#12](https://github.com/opengeospatial/ets-wms11/pull/12) - Remove normalize-string, substring-before; Replaced with contain
  * [#9](https://github.com/opengeospatial/ets-wms11/pull/9)- Fix for issue LayerNotDefined - Assertion #5  
  * [#6](https://github.com/opengeospatial/ets-wms11/issues/6)- Adjust configuration
  * [#10](https://github.com/opengeospatial/ets-wms11/pull/10)- Fix issues with reference implementations

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
