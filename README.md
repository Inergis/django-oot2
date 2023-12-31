# OpenOffice.org Writer template rendering

https://pypi.org/project/django-oot/ maded compatible with Django 2.2 and Python 3.6


# Installation

To install this application:

 * Put it in a directory *oot* inside your project.

 * Include ``'oot'`` in ``settings.INSTALLED_APPS``.

# Usage

For rendering an instance of a model into an OpenOffice.org Writer document:

 * Create an instance of the ``WriterTemplate`` model, either manually in the
    shell, using fixtures or through the admin. Choose the right content type
    for the objects you want to render.

 * Use the ``{% writer_templates obj %}`` *templatetag* wherever you wish to
    include a link for rendering an object into a Writer document.
