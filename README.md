# Practicum
This is test for Practicum

## Namespaces
* **dc:** http://purl.org/dc/elements/1.1/ 
* **dcterms:**  http://purl.org/dc/terms/ 
* **owl:** http://purl.org/dc/terms/ 
* **ual:** http://terms.library.ualberta.ca/  

## Definitions
   **acceptedValue** values belonging to properties with restricted value parameters (only those displayed on form)  
   **comments** Avalon specific instructions for using or questions about this property  
   **definedBy** a link to the Avalon ontology, including a general description of the property  
   **dataType** the kinds of values permitted for use by the property: 'text', 'enumerated text' (i.e. non-URI drop-down), 'uri' (i.e. dropdown with URI), 'auto' (generated by application logic)  
   **display** does this property appear when an object is displayed to the user? (boolean)  
   **displayLabel** if this object is displayed to the user, what is the label used to describe the property in the display?  
   **facet** is this property faceted in SOLR? (boolean)  
   **indexAs** another property with which this property should be indexed in SOLR  
   **onForm** does this property appear on the form when a user creates a new resource? (boolean)  
   **propertyName** an informal name for describing the property  
   **repeat** can this property occur more than once? (boolean)  
   **required** is the property required to have a value? (boolean)  
   **search** is this property searchable in Avalon? (boolean)  
   **sort** is this property sortable in SOLR? (boolean)  
### required 
  * creator  
  * subject (topical)
  * created (date issued)
  * language
  * title 
  * genre 
  * (sortYear) (not really know how this relate)
  * terms of use (or license)
  * license (or terms of use)

### repeat
  * bibliographic ID
  * other identifier
  * **creator**
  * Ccntributor
  * **genre**
  * publisher
  * **language**
  * **subject (topical)**
  * geographic subject
  * temporal subject
  * **file**

### display
### facet
### indexAs
### onForm
### search
### sort
  * title
  * created
  * sortYear
  * subject
  * creator
