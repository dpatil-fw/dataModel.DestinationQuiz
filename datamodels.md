# Race

This entity contains a harmonised description of a Race
-  `name`: Property. The name of the race
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `refQuestions`: Property. An array of all questions for this race.
   -  Attribute type: **Relationship**. 
   -  Required
-  `location`: 
   -  Attribute type: **GeoProperty**. [Point](https://purl.org/geojson/vocab#Point)
   -  Required
-  `description`: A description of this item
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `id`: Unique identifier of the entity
   -  Attribute type: **Property**. 
   -  Required
-  `owner`: A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)
   -  Attribute type: **Property**. 
   -  Optional
-  `seeAlso`: list of uri pointing to additional resources about the item
   -  Attribute type: **Property**. 
   -  Optional
-  `refSeeAlso`: List of references to one or more related entities.
   -  Attribute type: **Property**. [URL](https://schema.org/URL)
   -  Optional
-  `type`: NGSI Entity type. It has to be Race. One of : `Race`.
   -  Attribute type: **Property**. 
   -  Required



# Question

This entity contains a harmonised description of a Question
-  `questionText`: Property. Question entry for the quiz
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `options`: Property. Model:'https://schema.org/Text'. Answer options provided for the question.
   -  Attribute type: **Property**. 
   -  Required
-  `answerOption`: Property. The correct answer from the options list.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `location`: 
   -  Attribute type: **GeoProperty**. [Point](https://purl.org/geojson/vocab#Point)
   -  Required
-  `images`: Property. Model:'https://schema.org/URL'. URL of the image of the place.
   -  Attribute type: **Property**. 
   -  Optional
-  `description`: A description of this item
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `id`: Unique identifier of the entity
   -  Attribute type: **Property**. 
   -  Required
-  `owner`: A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)
   -  Attribute type: **Property**. 
   -  Optional
-  `seeAlso`: list of uri pointing to additional resources about the item
   -  Attribute type: **Property**. 
   -  Optional
-  `refSeeAlso`: List of references to one or more related entities.
   -  Attribute type: **Property**. [URL](https://schema.org/URL)
   -  Optional
-  `type`: NGSI Entity type. It has to be Question. One of : `Question`.
   -  Attribute type: **Property**. 
   -  Required



## Examples

### OK


