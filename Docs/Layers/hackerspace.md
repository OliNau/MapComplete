

 hackerspace 
=============



<img src='https://mapcomplete.osm.be/./assets/themes/hackerspaces/glider.svg' height="100px"> 

Hackerspace






  - This layer is shown at zoomlevel **8** and higher




#### Themes using this layer 





  - [hackerspaces](https://mapcomplete.osm.be/hackerspaces)
  - [personal](https://mapcomplete.osm.be/personal)




 Basic tags for this layer 
---------------------------



Elements must have the all of following tags to be shown on this layer:



  - <a href='https://wiki.openstreetmap.org/wiki/Key:leisure' target='_blank'>leisure</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:leisure%3Dhackerspace' target='_blank'>hackerspace</a>


[Execute on overpass](http://overpass-turbo.eu/?Q=%5Bout%3Ajson%5D%5Btimeout%3A90%5D%3B(%20%20%20%20nwr%5B%22leisure%22%3D%22hackerspace%22%5D(%7B%7Bbbox%7D%7D)%3B%0A)%3Bout%20body%3B%3E%3Bout%20skel%20qt%3B)



 Supported attributes 
----------------------



Warning: 

this quick overview is incomplete



attribute | type | values which are supported by this layer
----------- | ------ | ------------------------------------------
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/hackerspace#values) [hackerspace](https://wiki.openstreetmap.org/wiki/Key:hackerspace) | Multiple choice | [makerspace](https://wiki.openstreetmap.org/wiki/Tag:hackerspace%3Dmakerspace) [](https://wiki.openstreetmap.org/wiki/Tag:hackerspace%3D)
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/name#values) [name](https://wiki.openstreetmap.org/wiki/Key:name) | [string](../SpecialInputElements.md#string) | 
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/website#values) [website](https://wiki.openstreetmap.org/wiki/Key:website) | [url](../SpecialInputElements.md#url) | 
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/email#values) [email](https://wiki.openstreetmap.org/wiki/Key:email) | [email](../SpecialInputElements.md#email) | 
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/phone#values) [phone](https://wiki.openstreetmap.org/wiki/Key:phone) | [phone](../SpecialInputElements.md#phone) | 
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/opening_hours#values) [opening_hours](https://wiki.openstreetmap.org/wiki/Key:opening_hours) | [opening_hours](../SpecialInputElements.md#opening_hours) | [24/7](https://wiki.openstreetmap.org/wiki/Tag:opening_hours%3D24/7)
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/wheelchair#values) [wheelchair](https://wiki.openstreetmap.org/wiki/Key:wheelchair) | Multiple choice | [designated](https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Ddesignated) [yes](https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Dyes) [limited](https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Dlimited) [no](https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Dno)
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/drink:club-mate#values) [drink:club-mate](https://wiki.openstreetmap.org/wiki/Key:drink:club-mate) | Multiple choice | [yes](https://wiki.openstreetmap.org/wiki/Tag:drink:club-mate%3Dyes) [no](https://wiki.openstreetmap.org/wiki/Tag:drink:club-mate%3Dno)
[<img src='https://mapcomplete.osm.be/assets/svg/statistics.svg' height='18px'>](https://taginfo.openstreetmap.org/keys/start_date#values) [start_date](https://wiki.openstreetmap.org/wiki/Key:start_date) | [date](../SpecialInputElements.md#date) | 




### is_makerspace 



The question is  Is this a hackerspace or a makerspace?





  - This is a makerspace corresponds with  <a href='https://wiki.openstreetmap.org/wiki/Key:hackerspace' target='_blank'>hackerspace</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:hackerspace%3Dmakerspace' target='_blank'>makerspace</a>
  - This is a traditional (software oriented) hackerspace corresponds with  




### hackerspaces-name 



The question is  What is the name of this hackerspace?

This rendering asks information about the property  [name](https://wiki.openstreetmap.org/wiki/Key:name) 

This is rendered with  This hackerspace is named <b>{name}</b>





### website 



The question is  What is the website of {title()}?

This rendering asks information about the property  [website](https://wiki.openstreetmap.org/wiki/Key:website) 

This is rendered with  <a href='{website}' target='_blank'>{website}</a>





  - <a href='{contact:website}' target='_blank'>{contact:website}</a> corresponds with  contact:website~^..*$
  - This option cannot be chosen as answer




### email 



The question is  What is the email address of {title()}?

This rendering asks information about the property  [email](https://wiki.openstreetmap.org/wiki/Key:email) 

This is rendered with  <a href='mailto:{email}' target='_blank'>{email}</a>





  - <a href='mailto:{contact:email}' target='_blank'>{contact:email}</a> corresponds with  contact:email~^..*$
  - This option cannot be chosen as answer




### phone 



The question is  What is the phone number of {title()}?

This rendering asks information about the property  [phone](https://wiki.openstreetmap.org/wiki/Key:phone) 

This is rendered with  <a href='tel:{phone}'>{phone}</a>





  - <a href='tel:{contact:phone}'>{contact:phone}</a> corresponds with  contact:phone~^..*$
  - This option cannot be chosen as answer




### hackerspaces-opening_hours 



The question is  When is this hackerspace opened?

This rendering asks information about the property  [opening_hours](https://wiki.openstreetmap.org/wiki/Key:opening_hours) 

This is rendered with  {opening_hours_table()}





  - Opened 24/7 corresponds with  <a href='https://wiki.openstreetmap.org/wiki/Key:opening_hours' target='_blank'>opening_hours</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:opening_hours%3D24/7' target='_blank'>24/7</a>




### wheelchair-access 



The question is  Is this place accessible with a wheelchair?





  - This place is specially adapted for wheelchair users corresponds with  <a href='https://wiki.openstreetmap.org/wiki/Key:wheelchair' target='_blank'>wheelchair</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Ddesignated' target='_blank'>designated</a>
  - This place is easily reachable with a wheelchair corresponds with  <a href='https://wiki.openstreetmap.org/wiki/Key:wheelchair' target='_blank'>wheelchair</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Dyes' target='_blank'>yes</a>
  - It is possible to reach this place in a wheelchair, but it is not easy corresponds with  <a href='https://wiki.openstreetmap.org/wiki/Key:wheelchair' target='_blank'>wheelchair</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Dlimited' target='_blank'>limited</a>
  - This place is not reachable with a wheelchair corresponds with  <a href='https://wiki.openstreetmap.org/wiki/Key:wheelchair' target='_blank'>wheelchair</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:wheelchair%3Dno' target='_blank'>no</a>




### hs-club-mate 



The question is  Does this hackerspace serve Club Mate?





  - This hackerspace serves club mate corresponds with  <a href='https://wiki.openstreetmap.org/wiki/Key:drink:club-mate' target='_blank'>drink:club-mate</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:drink:club-mate%3Dyes' target='_blank'>yes</a>
  - This hackerspace does not serve club mate corresponds with  <a href='https://wiki.openstreetmap.org/wiki/Key:drink:club-mate' target='_blank'>drink:club-mate</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:drink:club-mate%3Dno' target='_blank'>no</a>




### hackerspaces-start_date 



The question is  When was this hackerspace founded?

This rendering asks information about the property  [start_date](https://wiki.openstreetmap.org/wiki/Key:start_date) 

This is rendered with  This hackerspace was founded at {start_date}

 

This document is autogenerated from [assets/layers/hackerspace/hackerspace.json](https://github.com/pietervdvn/MapComplete/blob/develop/assets/layers/hackerspace/hackerspace.json)