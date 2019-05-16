# jsonLdSPA
A minimal single page application framework that uses Json-LD/schema.org as data container to render a navigable content repository.

It is a simple proof of concept to use a single-source-of-data for a simple SinglePageApplication.
Content is stored within the page as a Json-LD structure, which is easily parsed by search engines and other tools that parse and use microformats.

However, to avoid redundancy, I would to test if this can be used as the single source of content for a complete set of web views.

This approach can be used to either generate a single html/javascript container to generate a full SPA and still be completely transparent to search engines and parsers.

And to keep it flexible for further use or integration with other frameworks I also aimed to use simple javascript without complex dependencies to other frameworks. For the displayable content, the exception in this example is to use MarkDown to create a structured view for the content involved. I deem that dependency simple and isolated enough to be exchanged with "insert-your-favorite-content-encoder".

