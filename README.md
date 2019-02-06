# Overview

This layer extends the base OpenStack layer and provides the base Ceph
configuration options dependencies and default reactive handlers for authoring
Ceph Charms.

# Where is the code?

The code for the `charms.openstack` module is developed at the following
location:

 - https://github.com/openstack/charms.openstack

The code specific for reactive Ceph charms is held in this layer, in the Ceph
reactive interfaces you choose to use, and a shared library called
`charms.ceph`:

 - https://github.com/openstack-charmers/charm-interface-ceph-client
 - https://github.com/openstack-charmers/charm-interface-rbd-mirror
 - https://github.com/openstack/charms.ceph
