# HAL - Hypertext Application Language

## A lean hypermedia type for RESTful APIs

HAL is a simple way of linking in REST APIs with either JSON or XML.

Essentially, HAL provides a set of conventions for expressing hyperlinks to, and embeddedness of, related resources - the rest of a HAL representation is just plain old JSON or XML. 

This repo contains a formalised specification of HAL (see [hal\_specification.md][1]).

For a friendlier, more pracitcal introduction to HAL you can read this article: [JSON Linking with HAL][2].

## Discussion Group

If you have any questions or feedback about HAL, you can message the [HAL-discuss mailing list][3]. 

## Contributing
If you think some part of the spec needs changing, just fork this repo
and raise a pull request with your changes.

## Code
* [(PHP) Hal Library][4]
* [(C#) Hal.Net][5]
* [(C#) WCF Media Type Formatter][6]
* [(Java) HalBuilder][7]


 [1]: https://github.com/mikekelly/hal_specification/blob/master/hal_specification.md
 [2]: http://blog.stateless.co/post/13296666138/json-linking-with-hal
 [3]: http://groups.google.com/group/hal-discuss
 [4]: https://github.com/zircote/Hal
 [5]: https://github.com/talios/halbuilder
 [6]: http://hal.codeplex.com/
 [7]: https://bitbucket.org/smichelotti/hal-media-type