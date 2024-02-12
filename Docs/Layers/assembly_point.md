[//]: # (WARNING: this file is automatically generated. Please find the sources at the bottom and edit those sources)

 assembly_point 
================





This layer contains assembly points and waiting areas where all employees, passengers or a large crowd assemble in case of an emergency.






  - This layer is shown at zoomlevel **10** and higher




#### Themes using this layer 





  - [disaster_response](https://mapcomplete.org/disaster_response)
  - [personal](https://mapcomplete.org/personal)




 Basic tags for this layer 
---------------------------



Elements must match the expression **<a href='https://wiki.openstreetmap.org/wiki/Key:emergency' target='_blank'>emergency</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:emergency%3Dassembly_point' target='_blank'>assembly_point</a>**

[Execute on overpass](http://overpass-turbo.eu/?Q=%5Bout%3Ajson%5D%5Btimeout%3A90%5D%3B%28%20%20%20%20nwr%5B%22emergency%22%3D%22assembly_point%22%5D%28%7B%7Bbbox%7D%7D%29%3B%0A%29%3Bout%20body%3B%3E%3Bout%20skel%20qt%3B)



 Supported attributes 
----------------------



Warning: 

this quick overview is incomplete



attribute | type | values which are supported by this layer
----------- | ------ | ------------------------------------------
[<img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/id#values) [id](https://wiki.openstreetmap.org/wiki/Key:id) | Multiple choice | 
[<img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/name#values) [name](https://wiki.openstreetmap.org/wiki/Key:name) | [string](../SpecialInputElements.md#string) | 
[<img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/operator#values) [operator](https://wiki.openstreetmap.org/wiki/Key:operator) | [string](../SpecialInputElements.md#string) | 




### just_created 



This element shows a 'thank you' that the contributor has recently created this element

This tagrendering has no question and is thus read-only





  - *You just created this element! Thanks for sharing this info with the world and helping people worldwide.*  corresponds with  id~.+


This tagrendering is only visible in the popup if the following condition is met: `_last_edit:passed_time<300 & (_version_number= | <a href='https://wiki.openstreetmap.org/wiki/Key:_version_number' target='_blank'>_version_number</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:_version_number%3D1' target='_blank'>1</a>) & _backend~.+`

This tagrendering has labels  `added_by_default`



### images 



This block shows the known images which are linked with the `image`-keys, but also via `mapillary` and `wikidata` and shows the button to upload new images

This tagrendering has no question and is thus read-only





### assembly_point_name 



The question is  *What is the name of this assembly point?*

This rendering asks information about the property  [name](https://wiki.openstreetmap.org/wiki/Key:name) This is rendered with  `This assembly point is named <b>{name}</b>`



### assembly_point_operator 



The question is  *What organization operates this assembly point?*

This rendering asks information about the property  [operator](https://wiki.openstreetmap.org/wiki/Key:operator) This is rendered with  `This assembly point is operated by <b>{operator}</b>`



### disaster_type 



The question is  *For which disaster type is this assembly point meant?*





  - *Earthquake*  corresponds with  <a href='https://wiki.openstreetmap.org/wiki/Key:assembly_point:earthquake' target='_blank'>assembly_point:earthquake</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:assembly_point:earthquake%3Dyes' target='_blank'>yes</a>
  - Unselecting this answer will add assembly_point:earthquake=
  - *Flood*  corresponds with  <a href='https://wiki.openstreetmap.org/wiki/Key:assembly_point:flood' target='_blank'>assembly_point:flood</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:assembly_point:flood%3Dyes' target='_blank'>yes</a>
  - Unselecting this answer will add assembly_point:flood=
  - *Fire*  corresponds with  <a href='https://wiki.openstreetmap.org/wiki/Key:assembly_point:fire' target='_blank'>assembly_point:fire</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:assembly_point:fire%3Dyes' target='_blank'>yes</a>
  - Unselecting this answer will add assembly_point:fire=
  - *Landslide*  corresponds with  <a href='https://wiki.openstreetmap.org/wiki/Key:assembly_point:landslide' target='_blank'>assembly_point:landslide</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:assembly_point:landslide%3Dyes' target='_blank'>yes</a>
  - Unselecting this answer will add assembly_point:landslide=




### leftover-questions 



This tagrendering has no question and is thus read-only





### minimap 



Shows a small map with the feature. Added by default to every popup

This tagrendering has no question and is thus read-only





### move-button 



This tagrendering has no question and is thus read-only





### last_edit 



Gives some metainfo about the last edit and who did edit it - rendering only

This tagrendering has no question and is thus read-only



This tagrendering is only visible in the popup if the following condition is met: `_last_edit:changeset~.+ & _last_edit:contributor~.+`

This tagrendering has labels  `added_by_default`



### favourite_status 



This tagrendering has no question and is thus read-only





### qr_code 



This tagrendering has no question and is thus read-only



This tagrendering has labels  `added_by_default`



### share 



This tagrendering has no question and is thus read-only



This tagrendering has labels  `added_by_default`



### all-tags 



This tagrendering has no question and is thus read-only

 

This document is autogenerated from [assets/layers/assembly_point/assembly_point.json](https://github.com/pietervdvn/MapComplete/blob/develop/assets/layers/assembly_point/assembly_point.json)