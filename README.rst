===========
ImgOptimize
===========

ImgOptimize use tools for optimize images and reduce size of file.


Install
=======

ImgOptimize is simple shell script and can execute directly. You can copy file
``imgoptimize`` for your ``PATH`` too.

According to format of image, external tool is necessary. You can check
external tool in `Supported Format <#supported-formats>`_.


Supported Formats
=================

====  =============
Type  External Tool
====  =============
JPEG  jpegtran
PNG   optipng
GIF   gifsicle
====  =============


Example of Use
==============

Call ``imgoptimize`` with images as arguments. One or more images can pass.

.. code-block:: sh

  imgoptimize file.jpg
  imgoptimize file.png
  imgoptimize file.jpg file.png
