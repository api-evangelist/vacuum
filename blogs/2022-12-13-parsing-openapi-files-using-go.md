---
title: "Parsing OpenAPI files using go"
url: "https://quobix.com/articles/parsing-openapi-using-go/"
date: "2022-12-13"
feed_url: "https://quobix.com/articles/index.xml"
---
Updated Jun 24th 2024 : The API for iterating over maps in libopenapi was changed in v0.14 to use ordered maps, instead of regular maps. This change was made to ensure that the order of items in the map is preserved when rendering back out the OpenAPI specification. A few folks reported issues with this blog here and here .
