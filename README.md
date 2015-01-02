# XML::NamespaceSupport

This module offers a simple way to process namespaced XML names (unames)
from within any application that may need them. It also helps maintain a
prefix to namespace URI map, and provides a number of basic checks.

The model for this module is SAX2's NamespaceSupport class, readable at

http://www.saxproject.org/namespaces.html

It adds a few perlisations where we thought it appropriate, and supports the
Namespaces in XML 1.1 specification.

-- Robin Berjon <rberjon@cpan.org>
