###METADATA

In HTML the <meta> tag has no end tag, while in XHTML the <meta> tag must be properly closed.

```html
    <!-- GENERAL METADATA: -->
    <meta charset="utf-8" />
    <!-- character encoding -->
    <meta name="keywords" content="keyword, keyword, keyword"/>
    <!-- keywords for search engines: each keyword separated by a comma (~10 is a good number) -->
    <meta name="description" content="About your document: description"/>
    <!-- description of the web page -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge"/>
    <!-- specifies a version of Internet Explorer -->
    <meta name="viewport" content="width=device-width, initial-scale=1"/>
    <!-- responsive -->

    <!-- DUBLIN CORE: -->
    <meta name="DC.title" content="My document title"/>
    <meta name="DC.contributor" content=""/>
    <!-- person/organization responsible for making contributions to the content of the resource -->
    <meta name="DC.creator" content="" />
    <!-- person/organization responsible for making the content of the resource -->
    <meta name="DC.publisher" content=""/>
    <!-- person/organization responsible for making the resource available -->
    <meta name="DC.subject" content="keywords, key phrases, or classification codes, best using controlled vocabularies">
    <!-- comma separated (can be more than the keywords) -->
    <meta name="DC.description.abstract" content="About the document: description abstract"/>
    <meta name="DC.date" scheme="W3CDTF"  content=""/>
    <!-- date of creation or availability of the resource: yyyy-mm-dd -->
    <meta name="DC.type" content=""/>
    <!-- = book / blogPost / artwork / bookSection / audioRecording / presentation (cf Zotero’s types)  -->
    <meta name="DC.format" content="text/html"/>
    <meta name="DC.identifier" content=""/>
    <!-- for instance: URL / URI / DOI (Digital Object Identifier) / ISBN / ISSN / … -->
    <meta name="DC.identifier.URL" content="http://url.net"/>
    <meta name="DC.language" content="eng"/>
    <!-- RFC3066 + ISO 639-3 language standard: http://en.wikipedia.org/wiki/ISO_639:a -->
    <meta name="DC.source" content="http://url.net/">
    <!-- link to a resource from which the present resource is derived -->
    <meta name="DC.relation" content=""/>
    <!-- reference to a related resource (using its identifier) -->
    <meta name="DC.rights" content="http://url.net/legal/terms-of-use"/>
    <meta name="DC.bibliographicCitation" content="use a Chicago Manual of Style citation"/> <!-- doesn’t need editing -->

    <!-- FACEBOOK: -->
    <meta property="og:url" content="http://url.net/"/>
    <meta property="og:title" content="Title of the page"/>
    <meta property="og:image" content="http://url.net/path/to/image.png"/>
    <!-- generic image: the best is 1200 x 630px for big images, or 100px by 100px -->
    <meta property="og:site_name" content="Site Name"/>
    <meta property="og:description" content="About your document: description"/>
    <meta property="og:type" content="article" />

```

###MORE OPTIONS

```html
    <meta name="generator" content="" />
    <!-- specifies the software packages used to generate the document -->
    <meta name="coverage" content="" />
    <!-- spatial or temporal topic of the resource (numeric identifiers such as sets of coordinates or date ranges) -->
```

###References:

http://dublincore.org/documents/dces/
