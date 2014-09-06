riak-common
===========

This role is very simple -- it's only meant to prep riak-related roles (riak, riakcs, and stanchion) for installation.  It configures some riak related repositories and does some minor PAM configuration to allow the dependent roles to properly set ulimits.

**N.B.** This module has been branched to support the new package repositories introduced for Riak 2.0 release.  Users deploying Riak 1.x should use the latest 1.x release of this module while users of Riak 2.0 should use the latest 2.x release.  Riak CS and Stanchion can be properly installed using with the 1.x or 2.x releases.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

License
-------

Apache

Maintainer Information
------------------

- James Martin 
- Bryan Hunt (<bhunt@basho.com>)
- Hector Castro

