logBee app (on-premises)
=============================

logBee can be installed on-premises.

Hosting logBee locally, all the logs will be stored and accessible only from within your in-house servers.

Artifacts
------------------------

- logBee.Backend-{version}-{platform}.zip
- logBee.Frontend-{version}-{platform}.zip

Artifacts can be downloaded from `https://github.com/catalingavan/logBee-app <https://github.com/catalingavan/logBee-app>`_.

Installation prerequisites
------------------------------

Local server
~~~~~~~~~~~~~~~~~~~~~~~~

- IIS Web server with `ASP.NET Core Runtime 8 <https://dotnet.microsoft.com/en-us/download/dotnet/8.0>`_ installed
- `MongoDB Community Server <https://www.mongodb.com/try/download/community>`_ (version >= 6.0.x)

Microsoft Azure
~~~~~~~~~~~~~~~~~~~~~~~~

- SQL Database
- Azure Cosmos DB
- Storage account
- 2x App Services

Docker
~~~~~~~~~~~~~~~~~~~~~~~~

- `Docker Engine <https://docs.docker.com/engine/>`_


.. toctree::
   :hidden: 
   :maxdepth: 2
   :titlesonly:
   :includehidden:

   installation/index
   logBee-frontend/index
   logBee-backend/index

