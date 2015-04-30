# OpenShift MariaDB Cartridge
This cartridge is documented in the [Cartridge Guide](http://openshift.github.io/documentation/oo_cartridge_guide.html#mariadb).

### Installation

rhc cartridge add -a myapp http://cartreflect-claytondev.rhcloud.com/github/ranib/openshift-cartridge-mariadb
    
This cartridge was extracted from the OpenShift Origin repository here: https://github.com/openshift/origin-server and can be installed
as a downloadable cartridge.  It exposes both OPENSHIFT_MARIADB and OPENSHIFT_MYSQL environment variables for compatibility.
