============================
gstypo3/render-documentation
============================

Simplified installation and usage of the `TYPO3 official Docker image 
t3docs/render-documentation <https://github.com/t3docs/docker-render-documentation>`_
for rendering TYPO3 documentation using `ddev <https://github.com/drud/ddev/#ddev>`_.


Prerequisites
=============

As we are using a very common toolset for TYPO3 development, most people should
already fulfill this prerequisites and just can head to :ref:`quick-start`.

#. **Check System Requirements**: We support recent versions of macOS, Windows
   10, and Linux distributions that will run Docker (ddev requires Docker and
   docker-compose).
#. **Git Bash on Windows**: `Download <https://git-scm.com/download/win>`_ and
   install **Git** including **Git Bash**. It's recommended running **ddev**
   in a **Git Bash** shell on Windows.
#. **Install ddev and prerequisites**: Follow the instructions of the
   `ddev documentation <https://ddev.readthedocs.io/en/stable/#installation>`_.


.. _quick-start:

Quick Start
===========

#. **Download and extract**: Get the `latest ddev project files from
   Github <https://github.com/gstypo3/render-documentation/releases/latest>`_
   and extract the archive to an empty folder of your choice. (`Download from
   master <https://github.com/gstypo3/render-documentation/archive/master.zip>`_
   until first release)
#. **Copy the Documentation**: Copy an existing **Documentation** folder into
   the previously created folder.
#. **Render the Documentation**: Open a shell and run ``ddev t3rd makehtml``
#. **Review the Documentation**: Open a browser and head to the 
   `rendered Documentation <https://t3docs.ddev.site/>`_.


In-Depth Installation
=====================


Configuration
=============

