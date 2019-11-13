# Changelog

Here you can see an overview of changes between each release.

## Version 4.0.1_02

Released on November 14th, 2019.

* Upgraded `pygluu-containerlib` to show connection issue with Couchbase explicitly.

## Version 4.0.1_01

Released on November 1st, 2019.

* Upgraded to Gluu Server 4.0.1.

## Version 4.0.0_01

Released on October 22nd, 2019.

* Upgraded to Gluu Server 4.0.
* SSL certificate and key can be mounted directly without being overwritten by the self-signed certificate and key.

## Version 3.1.6_02

Released on May 10th, 2019.

* Alpine upgraded to v3.9. Ref: https://github.com/GluuFederation/gluu-docker/issues/71.

## Version 3.1.6_01

Released on April 29th, 2019.

* Upgraded to Gluu Server 3.1.6.

## Version 3.1.5_03

Released on May 10th, 2019.

* Alpine upgraded to v3.9. Ref: https://github.com/GluuFederation/gluu-docker/issues/71.

## Version 3.1.5_02

Released on April 9th, 2019.

* Added license info on container startup.

## Version 3.1.5_01

Released on March 23rd, 2019.

* Upgraded to Gluu Server 3.1.5.

## Version 3.1.4_01

Released on November 12th, 2018.

* Upgraded to Gluu Server 3.1.4.

## Version 3.1.3_07

Released on September 27th, 2018.

* Removed deprecated `ssl on` directive.
* Removed unsecure SSL protocol TLSv1.

## Version 3.1.3_06

Released on September 18th, 2018.

* Changed base image to use Alpine 3.8.1.

## Version 3.1.3_05

Released on September 15th, 2018.

* Disable IPv6 support.

## Version 3.1.3_04

Released on September 12th, 2018.

* Added feature to connect to secure Consul (HTTPS).

## Version 3.1.3_03

Released on August 31st, 2018.

* Added Tini to handle signal forwarding and reaping zombie processes.

## Version 3.1.3_02

Released on July 20th, 2018.

* Added wrapper to manage config via Consul KV or Kubernetes configmap.

## Version 3.1.3_01

Released on June 6th, 2018.

* Upgraded to Gluu Server 3.1.3.

## Version 3.1.2_01

Released on June 6th, 2018.

* Upgraded to Gluu Server 3.1.2.

## Version 3.1.1_rev1.0.0-beta3

Released on October 24th, 2017.

* Disabled CORS headers

## Version 3.1.1_rev1.0.0-beta2

Released on October 11th, 2017.

* Fixed incorrect URLs to oxAuth REST API.

## Version 3.1.1_rev1.0.0-beta1

Released on October 6th, 2017.

* Migrated to Gluu Server 3.1.1.

## Version 3.0.1_rev1.0.0-beta5

Released on August 25th, 2017.

* Fixed duplicated CORS headers that were already set by oxAuth upstream.

## Version 3.0.1_rev1.0.0-beta4

Released on August 21st, 2017.

* Added missing CORS headers. Reference: https://github.com/GluuFederation/docker-nginx/issues/1.

## Version 3.0.1_rev1.0.0-beta3

Released on August 16th, 2017.

* Fixed server directive to avoid redirect loop on port 80.

## Version 3.0.1_rev1.0.0-beta2

Released on August 14th, 2017.

* Fixed `proxy_pass` directive.

## Version 3.0.1_rev1.0.0-beta1

Released on July 7th, 2017.

* Added working nginx.
