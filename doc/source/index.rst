Welcome to |project| documentation
====================================

.. include:: index-introduction.rst

Contents:

.. toctree::
   :maxdepth: 2

   introduction/introduction
   environments/environments
   installation/installation
   basic_deployment/basic_deployment_cli
   containers_deployment/index
   post_deployment/post_deployment
   advanced_deployment/features
   advanced_deployment/baremetal_nodes
   advanced_deployment/backends
   advanced_deployment/custom
   troubleshooting/troubleshooting
   validations/validations
   mistral-api/mistral-api
   developer/developer
   contributions/contributions


Documentation Conventions
=========================

Some steps in the following instructions only apply to certain environments,
such as deployments to real baremetal and deployments using Red Hat Enterprise
Linux (RHEL). These steps are marked as follows:

.. admonition:: RHEL
   :class: rhel

   Step that should only be run when using RHEL

.. admonition:: RHEL Portal Registration
   :class: portal

   Step that should only be run when using RHEL Portal Registration

.. admonition:: RHEL Satellite Registration
   :class: satellite

   Step that should only be run when using RHEL Satellite Registration

.. admonition:: CentOS
   :class: centos

   Step that should only be run when using CentOS

.. admonition:: Baremetal
   :class: baremetal

   Step that should only be run when deploying to baremetal

.. admonition:: Virtual
   :class: virtual

   Step that should only be run when deploying to virtual machines

.. admonition:: Ceph
   :class: ceph

   Step that should only be run when deploying Ceph for use by the Overcloud

.. admonition:: Source
   :class: source

   Step that should only be run when choosing to use some components directly
   from their git source code repositories instead of packages.

.. admonition:: Stable Branch
   :class: stable

   Step that should only be run when choosing to use components from their
   stable branches rather than using packages/source based on current master.

.. admonition:: Mitaka
   :class: mitaka

   Step that should only be run when installing from the Mitaka stable branch.

.. admonition:: Newton
   :class: newton

   Step that should only be run when installing from the Newton stable branch.

.. admonition:: Ocata
   :class: ocata

   Step that should only be run when installing from the Ocata stable branch.

.. admonition:: SSL
   :class: ssl

   Step that should only be run when deploying with SSL OpenStack endpoints

.. admonition:: Self-Signed SSL
   :class: selfsigned

   Step that should only be run when deploying with SSL and a self-signed certificate.

.. admonition:: Validations

   Steps that will run the pre and post-deployment validations

Any such steps should *not* be run if the target environment does not match
the section marking.
