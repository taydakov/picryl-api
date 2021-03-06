# Picryl API 2.0

Picryl API provides programmatic access to Picryl content.

The API is REST API. Return format for all endpoints is JSON.

You can try our API in [console](http://api.getarchive.net/swagger) (http://api.getarchive.net/swagger)

***

## Basics

- **[Formats and Terms](https://github.com/picryl/picryl-api/blob/master/basics/formats_and_terms.md)**
- **[API Terms of Use](https://github.com/picryl/picryl-api/blob/master/basics/terms_of_use.md)**

## Endpoints

#### Photo Resources
- **[<code>GET</code> photos](https://github.com/picryl/picryl-api/blob/master/endpoints/photo/GET_photos.md)**
- **[<code>GET</code> photos/:id](https://github.com/picryl/picryl-api/blob/master/endpoints/photo/GET_photos_id.md)**


#### Collection Resources
- **[<code>GET</code> collections](https://github.com/picryl/picryl-api/blob/master/endpoints/collection/GET_collections.md)**
- **[<code>GET</code> collections/:id](https://github.com/picryl/picryl-api/blob/master/endpoints/collection/GET_collections_id.md)**
- **[<code>GET</code> collections/:id/photos](https://github.com/picryl/picryl-api/blob/master/endpoints/collection/GET_collections_id_photos.md)**

#### Tag Resources
- **[<code>GET</code> tags](https://github.com/picryl/picryl-api/blob/master/endpoints/tag/GET_tags.md)**

## Changes

* 2015-06-17 API 2.0 BETA release.
* 2015-06-30 New base path is api.getarchive.net.
* 2015-08-06 Fixed typo "tranding" in the tag list request.
* 2015-09-02 Collection resource added.
