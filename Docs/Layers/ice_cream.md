[//]: # (WARNING: this file is automatically generated. Please find the sources at the bottom and edit those sources)

 ice_cream 
===========





A place where ice cream is sold over the counter






  - This layer is shown at zoomlevel **0** and higher




#### Themes using this layer 





  - [icecream](https://mapcomplete.org/icecream)
  - [personal](https://mapcomplete.org/personal)
  - [shops](https://mapcomplete.org/shops)


This is a special layer - data is not sourced from OpenStreetMap



 Supported attributes 
----------------------



Warning: 

this quick overview is incomplete



attribute | type | values which are supported by this layer
----------- | ------ | ------------------------------------------
[<img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/id#values) [id](https://wiki.openstreetmap.org/wiki/Key:id) | Multiple choice | 
[<img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/name#values) [name](https://wiki.openstreetmap.org/wiki/Key:name) | [string](../SpecialInputElements.md#string) | 
[<img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/opening_hours#values) [opening_hours](https://wiki.openstreetmap.org/wiki/Key:opening_hours) | [opening_hours](../SpecialInputElements.md#opening_hours) | 
[<img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/phone#values) [phone](https://wiki.openstreetmap.org/wiki/Key:phone) | [phone](../SpecialInputElements.md#phone) | 
[<img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/email#values) [email](https://wiki.openstreetmap.org/wiki/Key:email) | [email](../SpecialInputElements.md#email) | 
[<img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/website#values) [website](https://wiki.openstreetmap.org/wiki/Key:website) | [url](../SpecialInputElements.md#url) | 
[<img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/diet:sugar_free#values) [diet:sugar_free](https://wiki.openstreetmap.org/wiki/Key:diet:sugar_free) | Multiple choice | [only](https://wiki.openstreetmap.org/wiki/Tag:diet:sugar_free%3Donly) [yes](https://wiki.openstreetmap.org/wiki/Tag:diet:sugar_free%3Dyes) [limited](https://wiki.openstreetmap.org/wiki/Tag:diet:sugar_free%3Dlimited) [no](https://wiki.openstreetmap.org/wiki/Tag:diet:sugar_free%3Dno)
[<img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/diet:lactose_free#values) [diet:lactose_free](https://wiki.openstreetmap.org/wiki/Key:diet:lactose_free) | Multiple choice | [only](https://wiki.openstreetmap.org/wiki/Tag:diet:lactose_free%3Donly) [yes](https://wiki.openstreetmap.org/wiki/Tag:diet:lactose_free%3Dyes) [limited](https://wiki.openstreetmap.org/wiki/Tag:diet:lactose_free%3Dlimited) [no](https://wiki.openstreetmap.org/wiki/Tag:diet:lactose_free%3Dno)
[<img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/diet:gluten_free#values) [diet:gluten_free](https://wiki.openstreetmap.org/wiki/Key:diet:gluten_free) | Multiple choice | [only](https://wiki.openstreetmap.org/wiki/Tag:diet:gluten_free%3Donly) [yes](https://wiki.openstreetmap.org/wiki/Tag:diet:gluten_free%3Dyes) [limited](https://wiki.openstreetmap.org/wiki/Tag:diet:gluten_free%3Dlimited) [no](https://wiki.openstreetmap.org/wiki/Tag:diet:gluten_free%3Dno)
[<img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/diet:vegan#values) [diet:vegan](https://wiki.openstreetmap.org/wiki/Key:diet:vegan) | Multiple choice | [only](https://wiki.openstreetmap.org/wiki/Tag:diet:vegan%3Donly) [yes](https://wiki.openstreetmap.org/wiki/Tag:diet:vegan%3Dyes) [limited](https://wiki.openstreetmap.org/wiki/Tag:diet:vegan%3Dlimited) [no](https://wiki.openstreetmap.org/wiki/Tag:diet:vegan%3Dno)
[<img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/wheelchair#values) [wheelchair](https://wiki.openstreetmap.org/wiki/Key:wheelchair) | Multiple choice | [designated](https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Ddesignated) [yes](https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Dyes) [limited](https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Dlimited) [no](https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Dno)




### just_created 



This element shows a 'thank you' that the contributor has recently created this element

This tagrendering has no question and is thus read-only





  - *You just created this element! Thanks for sharing this info with the world and helping people worldwide.*  corresponds with  `id~.+`


This tagrendering is only visible in the popup if the following condition is met: `_backend~.+ &_last_edit:passed_time<300 & |_version_number=1`



### images 



This block shows the known images which are linked with the `image`-keys, but also via `mapillary` and `wikidata` and shows the button to upload new images

This tagrendering has no question and is thus read-only





### 1 



The question is  *What is the name of this ice cream parlor?*

This rendering asks information about the property  [name](https://wiki.openstreetmap.org/wiki/Key:name) 

This is rendered with  `This ice cream parlor is named <b>{name}</b>`





### opening_hours 



The question is  *What are the opening hours of {title()}?*

This rendering asks information about the property  [opening_hours](https://wiki.openstreetmap.org/wiki/Key:opening_hours) 

This is rendered with  `<h3>Opening hours</h3>{opening_hours_table(opening_hours)}`





### phone 



The question is  *What is the phone number of {title()}?*

This rendering asks information about the property  [phone](https://wiki.openstreetmap.org/wiki/Key:phone) 

This is rendered with  `<a href='tel:{phone}'>{phone}</a>`





  - *<a href='tel:{contact:phone}'>{contact:phone}</a>*  corresponds with  `contact:phone~.+`
  - This option cannot be chosen as answer


This tagrendering has labels  `contact`



### email 



The question is  *What is the email address of {title()}?*

This rendering asks information about the property  [email](https://wiki.openstreetmap.org/wiki/Key:email) 

This is rendered with  `<a href='mailto:{email}' target='_blank' rel='noopener'>{email}</a>`





  - *<a href='mailto:{contact:email}' target='_blank' rel='noopener'>{contact:email}</a>*  corresponds with  `contact:email~.+`
  - This option cannot be chosen as answer


This tagrendering has labels  `contact`



### website 



The question is  *What is the website of {title()}?*

This rendering asks information about the property  [website](https://wiki.openstreetmap.org/wiki/Key:website) 

This is rendered with  `<a href='{website}' rel='nofollow noopener noreferrer' target='_blank'>{website}</a>`





  - *<a href='{contact:website}' rel='nofollow noopener noreferrer' target='_blank'>{contact:website}</a>*  corresponds with  `contact:website~.+`
  - This option cannot be chosen as answer


This tagrendering has labels  `contact`



### sugar_free 



The question is  *Does this shop have a sugar free offering?*





  - *This shop <b>only sells sugar free</b> products*  corresponds with  `diet:sugar_free=only`
  - *This shop has a big sugar free offering*  corresponds with  `diet:sugar_free=yes`
  - *This shop has a <b>limited sugar free</b> offering*  corresponds with  `diet:sugar_free=limited`
  - *This shop has no sugar free offering*  corresponds with  `diet:sugar_free=no`


This tagrendering has labels  `diets`



### lactose_free 



The question is  *Does {title()} have a lactose-free offering?*





  - *<b>Only sells lactose free</b> products*  corresponds with  `diet:lactose_free=only`
  - *Big lactose free offering*  corresponds with  `diet:lactose_free=yes`
  - *<b>Limited lactose free</b> offering*  corresponds with  `diet:lactose_free=limited`
  - *No lactose free offering*  corresponds with  `diet:lactose_free=no`


This tagrendering has labels  `diets`



### gluten_free 



The question is  *Does this shop have a gluten free offering?*





  - *This shop <b>only sells gluten free</b> products*  corresponds with  `diet:gluten_free=only`
  - *This shop has a big gluten free offering*  corresponds with  `diet:gluten_free=yes`
  - *This shop has a <b>limited gluten free</b> offering*  corresponds with  `diet:gluten_free=limited`
  - *This shop has no gluten free offering*  corresponds with  `diet:gluten_free=no`


This tagrendering has labels  `diets`



### vegan 



The question is  *Does this place offer a vegan option?*





  - *This place <b>only sells vegan</b> products*  corresponds with  `diet:vegan=only`
  - *This shop has a big vegan offering*  corresponds with  `diet:vegan=yes`
  - *This shop has a <b>limited vegan</b> offering*  corresponds with  `diet:vegan=limited`
  - *This shop has no vegan offering*  corresponds with  `diet:vegan=no`


This tagrendering has labels  `diets`



### payment-options 



The question is  *Which methods of payment are accepted here?*





  - *Cash is accepted here*  corresponds with  `payment:cash=yes`
  - Unselecting this answer will add <a href='https://wiki.openstreetmap.org/wiki/Key:payment:cash' target='_blank'>payment:cash</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:payment:cash%3Dno' target='_blank'>no</a>
  - *Payment cards are accepted here*  corresponds with  `payment:cards=yes`
  - Unselecting this answer will add <a href='https://wiki.openstreetmap.org/wiki/Key:payment:cards' target='_blank'>payment:cards</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:payment:cards%3Dno' target='_blank'>no</a>
  - *Payment by QR-code is possible here*  corresponds with  `payment:qr_code=yes`
  - Unselecting this answer will add <a href='https://wiki.openstreetmap.org/wiki/Key:payment:qr_code' target='_blank'>payment:qr_code</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:payment:qr_code%3Dno' target='_blank'>no</a>




### wheelchair-access 



The question is  *Is this place accessible with a wheelchair?*





  - *This place is specially adapted for wheelchair users*  corresponds with  `wheelchair=designated`
  - *This place is easily reachable with a wheelchair*  corresponds with  `wheelchair=yes`
  - *It is possible to reach this place in a wheelchair, but it is not easy*  corresponds with  `wheelchair=limited`
  - *This place is not reachable with a wheelchair*  corresponds with  `wheelchair=no`




### leftover-questions 



This tagrendering has no question and is thus read-only





### minimap 



Shows a small map with the feature. Added by default to every popup

This tagrendering has no question and is thus read-only





### last_edit 



Gives some metainfo about the last edit and who did edit it - rendering only

This tagrendering has no question and is thus read-only



This tagrendering is only visible in the popup if the following condition is met: `_last_edit:contributor~.+ &_last_edit:changeset~.+`



### all-tags 



This tagrendering has no question and is thus read-only

 

This document is autogenerated from [assets/layers/ice_cream/ice_cream.json](https://github.com/pietervdvn/MapComplete/blob/develop/assets/layers/ice_cream/ice_cream.json)