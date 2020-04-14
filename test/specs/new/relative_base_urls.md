---
baseUrl: "/base/"
---
#1 Absolutization of RFC 3986 URIs

#2 Absolute URI
[![section 4.3](http://example.com/logo)](http://example.com/)

#2 Network-path reference
[![section 4.2](//example.com/logo)](//example.com/)

#2 Absolute path
[![section 4.2](/path/to/img)](/path/to/content)

#2 Relative path
[![section 4.2](img)](content)

#2 Dot-relative path
[![section 3.3](./img)](./content)

[![section 3.3](../img)](../content)

#2 Same-document query
[![section 4.4](?type=image)](?)

#2 Same-document fragment
[![section 4.4](#img)](#)

#2 Empty
[section 4.2]()
