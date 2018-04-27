ipaconf role
==============

Description
-----------

This role is used by ipaserver role as dependency to configure the IPA server.

Variables
---------

**ipaconf_default_conf** - IPA configuration file.
 (string)

**ipaconf_basedn** -
 (string)

**ipaconf_realm** - The Kerberos realm of an existing IPA deployment.
 (string)

**ipaconf_domain** - The primary DNS domain of an existing IPA deployment.
(string)

**ipaconf_server** -
(string)

**ipaconf_hostname** -
(string)

Requirements
------------

freeipa-server v4.5 or later

Authors
-------

Thomas Woerner

Victor da Costa
