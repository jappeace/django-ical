# django-ical

[![ReadTheDocsWidget]][ReadTheDocs]

[ReadTheDocs]: http://django-ics.readthedocs.org/en/latest/?badge=latest
[ReadTheDocsWidget]: https://readthedocs.org/projects/django-ics/badge/?version=latest

django-ical is a simple library/framework for creating
[ical](http://www.ietf.org/rfc/rfc2445.txt) feeds based in Django's
[syndication feed
framework](https://docs.djangoproject.com/en/1.4/ref/contrib/syndication/).
This documentation is modeled after the documentation for the syndication feed
framework so you can think of it as a simple extension.

If you are familiar with the Django syndication feed framework you should be
able to be able to use django-ical fairly quickly. It works the same way as the
Django syndication framework but adds a few extension properties to support
iCalendar feeds.

django-ical uses the [icalendar](http://pypi.python.org/pypi/icalendar/)
library under the hood to generate iCalendar feeds.

## Requirements

* `Django <http://www.djangoproject.com/>`_ >= 1.3.4
* `icalendar <http://pypi.python.org/pypi/icalendar/>`_ >= 3.1
* `six <https://pypi.python.org/pypi/six>`_ is required for Django versions < 1.4.2
