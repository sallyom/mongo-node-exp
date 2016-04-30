Nodejs app created from OpenShift 2.2 cartridge migrated to OpenShift 3.x
-------------------------------------------------------------------------

**Modifications from v2 -> v3**

* Removed .openshift dir
* in server.js: self.ipaddress = '0.0.0.0';
* in server.js: self.port = 8080;
* in server.js: removed conditional ~L20-22 about undefined self.ipaddress
