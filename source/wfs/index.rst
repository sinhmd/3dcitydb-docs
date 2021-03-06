Web Feature Service
===================

The OGC *Web Feature Service* Interface Standard (WFS) provides a
standardized and open interface for requesting geographic features
across the web using platform-independent calls. Rather than sharing
geographic information at the file level, for example, the WFS offers
direct fine-grained access to geographic information at the feature and
feature property level. Web feature services allow clients to only
retrieve or modify the data they are seeking, rather than retrieving a
file that contains the data they are seeking and possibly much more.

The 3D City Database offers a Web Feature Service interface allowing
web-based access to the 3D city objects stored in the database. WFS
clients can directly connect to this interface and retrieve 3D content
for a wide variety of purposes. Thus, users of the 3D City Database are
no longer limited to using the Importer/Exporter tool for data
retrieval. The WFS interface is platform-independent and
database-independent, and therefore can be easily used to build
CityGML-aware applications.

The 3D City Database WFS interface is implemented against the latest
*version 2.0* of the OGC Web Feature Service standard (OGC Doc. No.
09-025r2) and hence is compliant with ISO 19142:2010. Previous versions
of the WFS standard are not supported though. The implementation
currently satisfies the *Simple WFS* conformance class. The development
of the WFS is led by the company `virtualcitySYSTEMS GmbH <https://www.virtualcitysystems.de>`_
that offers an extended version of the WFS with additional
functionalities that go beyond the *Simple WFS* class (e.g., thematic
and spatial filter capabilities and transaction support). This
additional functionality may be fed back to the open source project in
future releases.

.. toctree::
   :maxdepth: 1

   system-requirements
   installation
   configuration
   functionality
   wfs-web-client

|apache_logo|\ The 3D City Database Web Feature Service is free software
under the *Apache License, Version 2.0*. See the LICENSE.txt file
shipped with the software for more details. For a copy of the Apache
License, Version 2.0, please visit http://www.apache.org/licenses/.

.. |apache_logo| image:: ../media/apache_logo.png
   :width: 0.97014in
   :height: 0.34583in
