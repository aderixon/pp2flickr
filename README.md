# Summary

`pp2flickr` is an adaptation of fp2flickr. It crawls individual albums from
a Photopost gallery and uploads each image found to Flickr. For more
information, read the inline POD using perldoc.

Note that Photopost galleries can vary somewhat in their format; you may
need to modify the code to handle particular instances (see the
`getFotoPics()` and `procImagePage()` subroutines). pp2flickr was written
to handle PhotographyBlog galleries as of May 2009.

Before use, pp2flickr must be configured with a Flickr API key and token
(see docs).

# Dependencies

pp2flickr requires `Flickr::Upload`, `LWP::UserAgent` and
`HTML::TreeBuilder` from CPAN.

# Support

pp2flickr has no ongoing support.
