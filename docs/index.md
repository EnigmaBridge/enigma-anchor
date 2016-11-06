## Get The Job Done

Login as the ***enigma-anchor*** user with `sudo - enigma-anchor`. Once you start the ***enigma-anchor***, you're welcome with the a short summary of the actual status of the certificate management and a list of actions that may be urgent.

You are then able to use one of the pre-defined commands:

* `create <domain name>` - creates a certificate for a given *domain name*; 
* `manage <domain name> [app]` - requests management of a domain, you can optionally add an application you want to manage - the default is a web server;
* `revoke <domain name> [app]` - revokes certificate for a particular domain (and application, if specified);
* `check [domain name] [app]` - returns certificates and their expiry dates;
* `list` - shows all the domains and applications managed by ***enigma-anchor***; 
* `admin` - show and allow changing contact details for reports;
* `kpi` - display key performance indicators (KPI).

