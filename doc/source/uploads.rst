=============
Image uploads
=============

.. toctree::
   :glob:
   :maxdepth: 2

   image/upload.rst


YAML file format
----------------
::

   uploads:
       - imagename: namespace/heat-docker-agents:latest
         uploader: docker
         pull_source: docker.io
         push_destination: localhost:8787
