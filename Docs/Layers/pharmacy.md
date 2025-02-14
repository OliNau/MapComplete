[//]: # (WARNING: this file is automatically generated. Please find the sources at the bottom and edit those sources)

# pharmacy

A layer showing pharmacies, which (probably) dispense prescription drugs

 - This layer is shown at zoomlevel **13** and higher

## Table of contents

1. [Themes using this layer](#themes-using-this-layer)
2. [Presets](#presets)
3. [Basic tags for this layer](#basic-tags-for-this-layer)
4. [Supported attributes](#supported-attributes)
  - [images](#images)
  - [reviews](#reviews)
  - [name](#name)
  - [opening_hours](#opening_hours)
  - [Opening hours](#opening-hours)
  - [phone](#phone)
  - [email](#email)
  - [website](#website)
  - [payment-options](#payment-options)
  - [wheelchair](#wheelchair)
  - [leftover-questions](#leftover-questions)
  - [move-button](#move-button)
  - [delete-button](#delete-button)
  - [lod](#lod)
5. [Filters](#filters)

## Themes using this layer

 - [disaster_response](https://mapcomplete.org/disaster_response)
 - [healthcare](https://mapcomplete.org/healthcare)
 - [onwheels](https://mapcomplete.org/onwheels)
 - [personal](https://mapcomplete.org/personal)
 - [shops](https://mapcomplete.org/shops)

## Presets

The following options to create new points are included:

 - **a pharmacy** which has the following tags:<a href='https://wiki.openstreetmap.org/wiki/Key:amenity' target='_blank'>amenity</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dpharmacy' target='_blank'>pharmacy</a>

## Basic tags for this layer

Elements must match the expression **<a href='https://wiki.openstreetmap.org/wiki/Key:amenity' target='_blank'>amenity</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dpharmacy' target='_blank'>pharmacy</a>**

[Execute on overpass](http://overpass-turbo.eu/?Q=%5Bout%3Ajson%5D%5Btimeout%3A90%5D%3B%28%20%20%20%20nwr%5B%22amenity%22%3D%22pharmacy%22%5D%28%7B%7Bbbox%7D%7D%29%3B%0A%29%3Bout%20body%3B%3E%3Bout%20skel%20qt%3B)

## Supported attributes

**Warning:**,this quick overview is incomplete,

| attribute | type | values which are supported by this layer |
-----|-----|----- |
| <a target="_blank" href='https://taginfo.openstreetmap.org/keys/name#values'><img src='https://mapcomplete.org/assets/svg/search.svg' height='18px'></a> <a target="_blank" href='https://taghistory.raifer.tech/?#***/name/'><img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'></a> [name](https://wiki.openstreetmap.org/wiki/Key:name) | [string](../SpecialInputElements.md#string) |  |
| <a target="_blank" href='https://taginfo.openstreetmap.org/keys/opening_hours#values'><img src='https://mapcomplete.org/assets/svg/search.svg' height='18px'></a> <a target="_blank" href='https://taghistory.raifer.tech/?#***/opening_hours/'><img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'></a> [opening_hours](https://wiki.openstreetmap.org/wiki/Key:opening_hours) | [opening_hours](../SpecialInputElements.md#opening_hours) |  |
| <a target="_blank" href='https://taginfo.openstreetmap.org/keys/phone#values'><img src='https://mapcomplete.org/assets/svg/search.svg' height='18px'></a> <a target="_blank" href='https://taghistory.raifer.tech/?#***/phone/'><img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'></a> [phone](https://wiki.openstreetmap.org/wiki/Key:phone) | [phone](../SpecialInputElements.md#phone) |  |
| <a target="_blank" href='https://taginfo.openstreetmap.org/keys/email#values'><img src='https://mapcomplete.org/assets/svg/search.svg' height='18px'></a> <a target="_blank" href='https://taghistory.raifer.tech/?#***/email/'><img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'></a> [email](https://wiki.openstreetmap.org/wiki/Key:email) | [email](../SpecialInputElements.md#email) |  |
| <a target="_blank" href='https://taginfo.openstreetmap.org/keys/website#values'><img src='https://mapcomplete.org/assets/svg/search.svg' height='18px'></a> <a target="_blank" href='https://taghistory.raifer.tech/?#***/website/'><img src='https://mapcomplete.org/assets/svg/statistics.svg' height='18px'></a> [website](https://wiki.openstreetmap.org/wiki/Key:website) | [url](../SpecialInputElements.md#url) |  |

### images
This block shows the known images which are linked with the `image`-keys, but also via `mapillary` and `wikidata` and shows the button to upload new images
_This tagrendering has no question and is thus read-only_
*{image_carousel()}{image_upload()}*

### reviews
Shows the reviews module (including the possibility to leave a review)
_This tagrendering has no question and is thus read-only_
*{create_review()}{list_reviews()}*

### name

The question is `What is the name of the pharmacy?`
*This pharmacy is called {name}* is shown if `name` is set

### opening_hours

The question is `What are the opening hours of {title()}?`
*<h3>Opening hours</h3>{opening_hours_table(opening_hours)}* is shown if `opening_hours` is set

 -  *Marked as closed for an unspecified time* is shown if with <a href='https://wiki.openstreetmap.org/wiki/Key:opening_hours' target='_blank'>opening_hours</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:opening_hours%3Dclosed' target='_blank'>closed</a>. _This option cannot be chosen as answer_

### phone

The question is `What is the phone number of {title()}?`
*{link(&LBRACEphone&RBRACE,tel:&LBRACEphone&RBRACE,,,,)}* is shown if `phone` is set

 - <img src='https://raw.githubusercontent.com/pietervdvn/MapComplete/develop/./assets/layers/questions/phone.svg' style='width: 3rem; height: 3rem'> *{link(&LBRACEcontact:phone&RBRACE,tel:&LBRACEcontact:phone&RBRACE,,,,)}* is shown if with contact:phone~.+. _This option cannot be chosen as answer_

This tagrendering has labels 
`contact`

### email

The question is `What is the email address of {title()}?`
*<a href='mailto:{email}' target='_blank' rel='noopener'>{email}</a>* is shown if `email` is set

 - <img src='https://raw.githubusercontent.com/pietervdvn/MapComplete/develop/./assets/svg/envelope.svg' style='width: 3rem; height: 3rem'> *<a href='mailto:{contact:email}' target='_blank' rel='noopener'>{contact:email}</a>* is shown if with contact:email~.+. _This option cannot be chosen as answer_
 - <img src='https://raw.githubusercontent.com/pietervdvn/MapComplete/develop/./assets/svg/envelope.svg' style='width: 3rem; height: 3rem'> *<a href='mailto:{operator:email}' target='_blank' rel='noopener'>{operator:email}</a>* is shown if with operator:email~.+. _This option cannot be chosen as answer_

This tagrendering has labels 
`contact`

### website

The question is `What is the website of {title()}?`
*<a href='{website}' rel='nofollow noopener noreferrer' target='_blank'>{website}</a>* is shown if `website` is set

 - <img src='https://raw.githubusercontent.com/pietervdvn/MapComplete/develop/./assets/layers/icons/website.svg' style='width: 3rem; height: 3rem'> *<a href='{contact:website}' rel='nofollow noopener noreferrer' target='_blank'>{contact:website}</a>* is shown if with contact:website~.+. _This option cannot be chosen as answer_

This tagrendering has labels 
`contact`

### payment-options

The question is `Which methods of payment are accepted here?`

 - <img src='https://raw.githubusercontent.com/pietervdvn/MapComplete/develop/./assets/layers/questions/cash.svg' style='width: 3rem; height: 3rem'> *Cash is accepted here* is shown if with <a href='https://wiki.openstreetmap.org/wiki/Key:payment:cash' target='_blank'>payment:cash</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:payment:cash%3Dyes' target='_blank'>yes</a>. Unselecting this answer will add <a href='https://wiki.openstreetmap.org/wiki/Key:payment:cash' target='_blank'>payment:cash</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:payment:cash%3Dno' target='_blank'>no</a>
 - <img src='https://raw.githubusercontent.com/pietervdvn/MapComplete/develop/./assets/layers/questions/payment_card.svg' style='width: 3rem; height: 3rem'> *Payment cards are accepted here* is shown if with <a href='https://wiki.openstreetmap.org/wiki/Key:payment:cards' target='_blank'>payment:cards</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:payment:cards%3Dyes' target='_blank'>yes</a>. Unselecting this answer will add <a href='https://wiki.openstreetmap.org/wiki/Key:payment:cards' target='_blank'>payment:cards</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:payment:cards%3Dno' target='_blank'>no</a>
 - <img src='https://raw.githubusercontent.com/pietervdvn/MapComplete/develop/./assets/layers/questions/qrcode.svg' style='width: 3rem; height: 3rem'> *Payment by QR-code is possible here* is shown if with <a href='https://wiki.openstreetmap.org/wiki/Key:payment:qr_code' target='_blank'>payment:qr_code</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:payment:qr_code%3Dyes' target='_blank'>yes</a>. Unselecting this answer will add <a href='https://wiki.openstreetmap.org/wiki/Key:payment:qr_code' target='_blank'>payment:qr_code</a>=<a href='https://wiki.openstreetmap.org/wiki/Tag:payment:qr_code%3Dno' target='_blank'>no</a>

### wheelchair

_This tagrendering has no question and is thus read-only_
*wheelchair*

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
| drive-through.0 | Has drive through | drive_through=yes |

| id | question | osmTags |
-----|-----|----- |
| dispensing.0 | Pharmacy able to provide prescription drugs | dispensing=yes |

| id | question | osmTags |
-----|-----|----- |
| open_now.0 | Open now | _isOpen=yes |

| id | question | osmTags |
-----|-----|----- |
| accepts_cash.0 | Accepts cash | payment:cash=yes |

| id | question | osmTags |
-----|-----|----- |
| accepts_cards.0 | Accepts payment cards | payment:cards=yes |



This document is autogenerated from [assets/layers/pharmacy/pharmacy.json](https://github.com/pietervdvn/MapComplete/blob/develop/assets/layers/pharmacy/pharmacy.json)
