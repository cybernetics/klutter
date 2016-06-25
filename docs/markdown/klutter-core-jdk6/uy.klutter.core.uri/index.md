[uy.klutter.core.uri](.)


## Package uy.klutter.core.uri

### Types

|&nbsp;|&nbsp;|
|---|---|
| [ImmutableUri](-immutable-uri/index.md) | `interface ImmutableUri` |
| [UriBuilder](-uri-builder/index.md) | `class UriBuilder&nbsp;:&nbsp;[ImmutableUri](-immutable-uri/index.md)` |
| [UrlEncoding](-url-encoding/index.md) | `object UrlEncoding`<p>Converted to Kotlin from https://github.com/resteasy/Resteasy/blob/master/jaxrs/resteasy-jaxrs/src/main/java/org/jboss/resteasy/util/URLUtils.java<br/>Then with extra things added including a ported decoder from same library, query to maps, and more</p> |

### Functions

|&nbsp;|&nbsp;|
|---|---|
| [buildUri](build-uri.md) | `fun buildUri(uri:&nbsp;[URI](http://docs.oracle.com/javase/6/docs/api/java/net/URI.html)): [UriBuilder](-uri-builder/index.md)`<br/>`fun buildUri(uriString:&nbsp;String): [UriBuilder](-uri-builder/index.md)`<br/>`fun buildUri(url:&nbsp;[URL](http://docs.oracle.com/javase/6/docs/api/java/net/URL.html)): [UriBuilder](-uri-builder/index.md)`<br/>`fun buildUri(uri:&nbsp;[ImmutableUri](-immutable-uri/index.md)): [UriBuilder](-uri-builder/index.md)` |