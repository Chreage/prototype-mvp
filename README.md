prototype-mvp
=============

prototype minimum viable product


* The MVP of Chreage is a list spatializer

For any list in entry, it returns a L-System that maps the contents as Spheres of diminishing radius in 2D

MVP 1.xxx will be L-Systems mapped in 2D, of increasing detail, assymetry, complexity and fetching the top Alexa Websites

** basically each click will just open a new tab of the corresponding site 
** there are 1 000 000 sites to map in total
*** if we take one single 2 branch L-system that is 2^20 = 1 048 576
*** if we take about six 3 branch L-systems that is 6*3^11 = 1 062 882


MVP 2.xxx will consist of adding volume to the 2D mappings, e.g. by using simplex noise parametered to the Alexa rankings

** notes on the "Island" rendering: 
*** let us adopt the following disposition by default:
**** 7 ISLAND
**** each ISLAND has 3 ISLET grouped together, separated by canals 
**** each ISLET has 5 sectors
**** each sector can have up to 3 L-systems



MVP 3.xxx will consist of the previous one, except that inside site contents will be mapped by L-systems as well: eg: within wikipedia, one query gives a L-system


MVP 4.xxx will incorporate the metasearch engine










-------------- this is now useless ---------------


* In parallel, one could start embedding Chromium in the interface. Versions embedding chromium using the CEF (Chromium Embedded Framework) will be called ".CEF"
* the CEF's webpage can be found here https://code.google.com/p/chromiumembedded/


* Once the Persistant world is generated, we will need to apply the list spatializer within domains (eg TED, Wikipedia, Youtube etc.). For example, the Wikipedia domain will be a space where any search will return a L-system mapping the results.    


