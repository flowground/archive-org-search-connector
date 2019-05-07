# ![LOGO](logo.png) Search Services MSP Connector

## Description

A generated MSP connector for the Search Services API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/archive.org/search/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T11:17:13+03:00

## API Description

API for Internet Archive's Search-related services


## Authorization

This API does not require authorization.

## Actions

### Fields that can be requested

#### Input Parameters
* `callback` - _optional_ - Specifies a JavaScript function func, for a JSON-P response. When provided, results are wrapped as `callback(data)`, and the returned MIME type is application/javascript. This causes the caller to automatically run the func with the JSON results as its argument.

### Return relevance-based results from search queries

#### Input Parameters
* `q` - _optional_ - Lucene-type search query
* `field` - _optional_ - Metadata field
* `size` - _optional_ - Number of query results to return
* `total_only` - _optional_ - Request total only; do not return hits
* `callback` - _optional_ - Specifies a JavaScript function func, for a JSON-P response. When provided, results are wrapped as `callback(data)`, and the returned MIME type is application/javascript. This causes the caller to automatically run the func with the JSON results as its argument.

### Scrape search results from Internet Archive, allowing a scrolling cursor

#### Input Parameters
* `q` - _optional_ - Lucene-type search query
* `field` - _optional_ - Metadata field
* `sort` - _optional_ - sort collations
* `size` - _optional_ - Number of query results to return
* `cursor` - _optional_ - Cursor for scrolling (used for subsequent calls)
* `total_only` - _optional_ - Request total only; do not return hits
* `callback` - _optional_ - Specifies a JavaScript function func, for a JSON-P response. When provided, results are wrapped as `callback(data)`, and the returned MIME type is application/javascript. This causes the caller to automatically run the func with the JSON results as its argument.

## License

flowground :- Telekom iPaaS / archive-org-search-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
