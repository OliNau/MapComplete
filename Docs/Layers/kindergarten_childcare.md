[//]: # (WARNING: this file is automatically generated. Please find the sources at the bottom and edit those sources)

# kindergarten_childcare

Shows kindergartens and preschools. Both are grouped in one layer, as they are regularly confused with each other

 - This layer is shown at zoomlevel **12** and higher

## Table of contents

1. [Themes using this layer](#themes-using-this-layer)
2. [Presets](#presets)
3. [Basic tags for this layer](#basic-tags-for-this-layer)
4. [Supported attributes](#supported-attributes)
  - [childcare-type](#childcare-type)
  - [name](#name)
  - [website](#website)
  - [email](#email)
  - [phone](#phone)
  - [opening_hours](#opening_hours)
  - [Opening hours](#opening-hours)
  - [capacity](#capacity)
  - [leftover-questions](#leftover-questions)
  - [move-button](#move-button)
  - [delete-button](#delete-button)
  - [lod](#lod)
5. [Filters](#filters)

## Themes using this layer

 - [education](https://mapcomplete.org/education)
 - [personal](https://mapcomplete.org/personal)

## Presets

The following options to create new points are included:

 - **a kindergarten** which has the following tags:<a href='https://wiki.openstreetmap.org/wiki/Key:amenity' target='_blank'>amenity</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dkindergarten' target='_blank'>kindergarten</a> & <a href='https://wiki.openstreetmap.org/wiki/Key:isced:level' target='_blank'>isced:level</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:isced:level%3D0' target='_blank'>0</a> & <a href='https://wiki.openstreetmap.org/wiki/Key:isced:2011:level' target='_blank'>isced:2011:level</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:isced:2011:level%3Dearly_childhood' target='_blank'>early_childhood</a>
 - **a childcare** which has the following tags:<a href='https://wiki.openstreetmap.org/wiki/Key:amenity' target='_blank'>amenity</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dkindergarten' target='_blank'>kindergarten</a>

## Basic tags for this layer

Elements must match **any** of the following expressions:

 - <a href='https://wiki.openstreetmap.org/wiki/Key:amenity' target='_blank'>amenity</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dchildcare' target='_blank'>childcare</a>
 - <a href='https://wiki.openstreetmap.org/wiki/Key:amenity' target='_blank'>amenity</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dkindergarten' target='_blank'>kindergarten</a>
 - <a href='https://wiki.openstreetmap.org/wiki/Key:isced:level:2011' target='_blank'>isced:level:2011</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:isced:level:2011%3Dearly_childhood' target='_blank'>early_childhood</a>

[Execute on overpass](http://overpass-turbo.eu/?Q=%5Bout%3Ajson%5D%5Btimeout%3A90%5D%3B%28%20%20%20%20nwr%5B%22amenity%22%3D%22childcare%22%5D%28%7B%7Bbbox%7D%7D%29%3B%0A%20%20%20%20nwr%5B%22amenity%22%3D%22kindergarten%22%5D%28%7B%7Bbbox%7D%7D%29%3B%0A%20%20%20%20nwr%5B%22isced%3Alevel%3A2011%22%3D%22early_childhood%22%5D%28%7B%7Bbbox%7D%7D%29%3B%0A%29%3Bout%20body%3B%3E%3Bout%20skel%20qt%3B)

## Supported attributes

**Warning:**,this quick overview is incomplete,

| attribute | type | values which are supported by this layer |
-----|-----|----- |
| <a target="_blank" href='https://taginfo.openstreetmap.org/keys/amenity#values'><img src='https://mapcomplete.org/assets/svg/search.svg' height='18px'></a> <a target="_blank" href='https://taghistory.raifer.tech/?#***/amenity/'><img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'></a> [amenity](https://wiki.openstreetmap.org/wiki/Key:amenity) | Multiple choice | [kindergarten](https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dkindergarten) [childcare](https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dchildcare) |
| <a target="_blank" href='https://taginfo.openstreetmap.org/keys/name#values'><img src='https://mapcomplete.org/assets/svg/search.svg' height='18px'></a> <a target="_blank" href='https://taghistory.raifer.tech/?#***/name/'><img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'></a> [name](https://wiki.openstreetmap.org/wiki/Key:name) | [string](../SpecialInputElements.md#string) |  |
| <a target="_blank" href='https://taginfo.openstreetmap.org/keys/website#values'><img src='https://mapcomplete.org/assets/svg/search.svg' height='18px'></a> <a target="_blank" href='https://taghistory.raifer.tech/?#***/website/'><img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'></a> [website](https://wiki.openstreetmap.org/wiki/Key:website) | [url](../SpecialInputElements.md#url) |  |
| <a target="_blank" href='https://taginfo.openstreetmap.org/keys/email#values'><img src='https://mapcomplete.org/assets/svg/search.svg' height='18px'></a> <a target="_blank" href='https://taghistory.raifer.tech/?#***/email/'><img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'></a> [email](https://wiki.openstreetmap.org/wiki/Key:email) | [email](../SpecialInputElements.md#email) |  |
| <a target="_blank" href='https://taginfo.openstreetmap.org/keys/phone#values'><img src='https://mapcomplete.org/assets/svg/search.svg' height='18px'></a> <a target="_blank" href='https://taghistory.raifer.tech/?#***/phone/'><img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'></a> [phone](https://wiki.openstreetmap.org/wiki/Key:phone) | [phone](../SpecialInputElements.md#phone) |  |
| <a target="_blank" href='https://taginfo.openstreetmap.org/keys/opening_hours#values'><img src='https://mapcomplete.org/assets/svg/search.svg' height='18px'></a> <a target="_blank" href='https://taghistory.raifer.tech/?#***/opening_hours/'><img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'></a> [opening_hours](https://wiki.openstreetmap.org/wiki/Key:opening_hours) | [opening_hours](../SpecialInputElements.md#opening_hours) |  |
| <a target="_blank" href='https://taginfo.openstreetmap.org/keys/capacity#values'><img src='https://mapcomplete.org/assets/svg/search.svg' height='18px'></a> <a target="_blank" href='https://taghistory.raifer.tech/?#***/capacity/'><img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'></a> [capacity](https://wiki.openstreetmap.org/wiki/Key:capacity) | [pnat](../SpecialInputElements.md#pnat) |  |

### childcare-type

The question is `What type of facility is this?`

 -  *This is a kindergarten (also known as <i>preschool</i>) where small kids receive early education.* is shown if with <a href='https://wiki.openstreetmap.org/wiki/Key:amenity' target='_blank'>amenity</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dkindergarten' target='_blank'>kindergarten</a>
 -  *This is a childcare facility, such as a nursery or daycare where small kids are looked after. They do not offer an education and are ofter run as private businesses* is shown if with <a href='https://wiki.openstreetmap.org/wiki/Key:amenity' target='_blank'>amenity</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dchildcare' target='_blank'>childcare</a>

### name

The question is `What is the name of this facility?`
*This facility is named <b>{name}</b>* is shown if `name` is set

### website

The question is `What is the website of {title()}?`
*<a href='{website}' rel='nofollow noopener noreferrer' target='_blank'>{website}</a>* is shown if `website` is set

 - <img src='https://raw.githubusercontent.com/pietervdvn/MapComplete/develop/./assets/layers/icons/website.svg' style='width: 3rem; height: 3rem'> *<a href='{contact:website}' rel='nofollow noopener noreferrer' target='_blank'>{contact:website}</a>* is shown if with contact:website~.+. _This option cannot be chosen as answer_

This tagrendering has labels 
`contact`

### email

The question is `What is the email address of {title()}?`
*<a href='mailto:{email}' target='_blank' rel='noopener'>{email}</a>* is shown if `email` is set

 - <img src='https://raw.githubusercontent.com/pietervdvn/MapComplete/develop/./assets/svg/envelope.svg' style='width: 3rem; height: 3rem'> *<a href='mailto:{contact:email}' target='_blank' rel='noopener'>{contact:email}</a>* is shown if with contact:email~.+. _This option cannot be chosen as answer_
 - <img src='https://raw.githubusercontent.com/pietervdvn/MapComplete/develop/./assets/svg/envelope.svg' style='width: 3rem; height: 3rem'> *<a href='mailto:{operator:email}' target='_blank' rel='noopener'>{operator:email}</a>* is shown if with operator:email~.+. _This option cannot be chosen as answer_

This tagrendering has labels 
`contact`

### phone

The question is `What is the phone number of {title()}?`
*{link(&LBRACEphone&RBRACE,tel:&LBRACEphone&RBRACE,,,,)}* is shown if `phone` is set

 - <img src='https://raw.githubusercontent.com/pietervdvn/MapComplete/develop/./assets/layers/questions/phone.svg' style='width: 3rem; height: 3rem'> *{link(&LBRACEcontact:phone&RBRACE,tel:&LBRACEcontact:phone&RBRACE,,,,)}* is shown if with contact:phone~.+. _This option cannot be chosen as answer_

This tagrendering has labels 
`contact`

### opening_hours

The question is `When is this childcare opened?`
*<h3>Opening hours</h3>{opening_hours_table(opening_hours)}* is shown if `opening_hours` is set

 -  *Marked as closed for an unspecified time* is shown if with <a href='https://wiki.openstreetmap.org/wiki/Key:opening_hours' target='_blank'>opening_hours</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:opening_hours%3Dclosed' target='_blank'>closed</a>. _This option cannot be chosen as answer_

This tagrendering is only visible in the popup if the following condition is met: <a href='https://wiki.openstreetmap.org/wiki/Key:amenity' target='_blank'>amenity</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dchildcare' target='_blank'>childcare</a>

### capacity

The question is `How much kids (at most) can be enrolled here?`
*This facility has room for {capacity} kids* is shown if `capacity` is set

### leftover-questions

_This tagrendering has no question and is thus read-only_
*{questions( ,)}*

### move-button

_This tagrendering has no question and is thus read-only_
*{move_button()}*

### delete-button

_This tagrendering has no question and is thus read-only_
*{delete_button()}*

### lod

_This tagrendering has no question and is thus read-only_
*{linked_data_from_website()}*

This tagrendering has labels 
`added_by_default`

## Filters

| id | question | osmTags |
-----|-----|----- |
| open_now.0 | Open now | _isOpen=yes |



This document is autogenerated from [assets/layers/kindergarten_childcare/kindergarten_childcare.json](https://github.com/pietervdvn/MapComplete/blob/develop/assets/layers/kindergarten_childcare/kindergarten_childcare.json)
