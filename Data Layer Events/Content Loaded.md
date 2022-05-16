# Content Loaded

### This event is part of the page load sequence, including virtual page loads in the case of single page apps, and must be pushed between the `Page Load Started` and `Page Load Completed` events.

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Content Loaded",
    "content": {
        "contentAuthor": "<contentAuthor>",
        "contentDate": "<contentDate>",
        "contentID": "<contentID>",
        "contentTitle": "<contentTitle>",
        "licensor": "<licensor>",
        "modifiedDate": "<modifiedDate>"
    },
    "items": [
        {
            "contentAuthor": "<contentAuthor>",
            "contentDate": "<contentDate>",
            "contentID": "<contentID>",
            "contentTitle": "<contentTitle>"
        }
    ]
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|content.contentAuthor|string|Unique identifer of the content author.|Betsy Ross, Ben Franklin, Howard Hughes, Tipper Gore|||||||
|content.contentDate|string|Date of the content's publication. ISO 8601 form \(YYYY-MM-DD\). Jan 1, 2019 is 2019-01-01|2001-12-22, 2011-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|content.contentID|string|Unique identifer of the content.||||||||
|content.contentTitle|string|Title of a piece of content. |50 ways to use jello, Another look at pandas, Year end giving|||||||
|content.licensor|string|The licensee or owner of content \(i.e. HBO\)|HBO, Disney|||||||
|content.modifiedDate|string|The last date that content was modified\/updated|1-1-2020, 2-2-2019|||||||
|items[n].contentAuthor|string|Unique identifer of the content author.|Betsy Ross, Ben Franklin, Howard Hughes, Tipper Gore|||||||
|items[n].contentDate|string|Date of the content's publication. ISO 8601 form \(YYYY-MM-DD\). Jan 1, 2019 is 2019-01-01|2001-12-22, 2001-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|items[n].contentID|string|Unique identifer of the content.||||||||
|items[n].contentTitle|string|Title of a piece of content. |50 ways to use jello, Another look at pandas, Year end giving|||||||




