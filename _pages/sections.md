---
layout: page
title: Sections
permalink: /sections/
header:
  image_fullwidth: front-page.jpg
---

Most of the sections listed below (ought to) contain sub-items, most of them with headlines, often also bylines and datelines. These sections are identified using the `element=` attribute.

Section name|element (or deprecated xml:id)|Usual page|Notes
**[Advertisements](https://dig-eg-gaz.github.io/advertisements/)** |various|1,2|Use templates
**[Daily Weather Report](https://dig-eg-gaz.github.io/boilerplates-and-tables/#daily-weather-report)** |`deg-el-dawr01`|2|[xml text](https://github.com/dig-eg-gaz/boilerplates/blob/master/boilerplates-text/daily-weather-report.xml)
**Telegrams / Wire Reports** (international news)|"wire"|2,3|Sometimes appears as "To-day's telegrams", but typically there is no heading for this section. Treat wire reports as individual divs (`type="wireReport"`), each with its own `<dateline>` and `<title>`. This section is sometimes spread over two pages; when this is the case, you can use the `next` and `prev` attributes.
**Local and General** |"local"|3|treat individual paragraphs as individual divs (`type="item"`), each with its own `<head>`.
**Sport and Play** |"sport"|3|Treat contents as items, each with own headline.
**Personal and Social** |"social"|3|Treat contents as paragraphs
**[Calendar of Coming Events](https://dig-eg-gaz.github.io/boilerplates-and-tables/#calendar-of-coming-events)** |`deg-el-coce01`|2-3|see [template](https://github.com/dig-eg-gaz/boilerplates/blob/master/boilerplates-text/calendar-of-coming-events.xml) for format
**Passenger List** |`deg-el-plst01`|3|Treat arrivals and departures as items.
**Visitors' List** |`deg-el-vlst01`|3|Treat each hotel as an item.
**Letters to the Editor** |`deg-el-lett01`|3|Treat each letter as an item, with `<byline>` and `<dateline>`
**Native Press Comments** |`deg-el-napc01`||
**The Khedive** |`deg-el-khed01`|3|
**Steamer Movements** |`deg-el-stmr01`||Treat contents as paragraphs.
**Army and Navy / Army of Occupation** |`deg-el-army01`||
**Egyptian Army** |`deg-el-egar01`||
**Our London Letter** |`deg-el-lonl01`||
**Our Paris Letter** |`deg-el-parl01`||
**Egyptian Share Market** |`deg-el-egsh01`||
**Bulletin de la bourse** |`deg-el-bdlb01`||French language
**Chronique Financiere** |`deg-el-chrf01`|4|French language
**Chronique Judiciare** |`deg-el-chrj01`|4|French language
**Shipping Movements** |`deg-el-ship01`|4|
**Mouvement Maritime** |`deg-el-moma01`|4|French language
**Council of Ministers** |`deg-el-cmin`|4|

## "Notes from" section:
These notes typically appear on page 3. They are sourced to "Our Own Correspondent". Treat individual stories as `<div type="item">`, each with its own `<head>`. It is not always clear how many stories belong to the section.

Place|xml:id|Notes
Port Said|`deg-el-nf-port01`|
Suez|`deg-el-nf-suez01`
Suakin|`deg-el-nf-suak01`
Khartoum|`deg-el-nf-khrt01`
Constantinople|`deg-el-nf-cnst01`|also appears as Constantinople Notes
Wadi Medani|`deg-el-nf-wame01`
Assiout|`deg-el-nf-assi01`
Luxor|`deg-el-nf-luxr01`|also appears as Luxor Notes
Cyprus|`deg-el-nf-cypr01`
Minet el Gamh|`deg-el-nf-miga01`
Fayoum|`deg-el-nf-faym01`|also appears as Fayoum Notes
The Sudan|`deg-el-nf-sudn01`
Kafr Zayat|`deg-el-nf-kfrz01`
Mena|`deg-el-nf-mena01`
Helouan|`deg-el-nf-hlwn01`
Keneh|`deg-el-nf-kena01`
Akhmin|`deg-el-nf-akhm01`

Others:
- Legal Notes
- Questions municipales
- Pith of the Press Comments
- Esbekieh Gardens
- Matters of Moment
- Naval Notes
- Egyptological Notes