---
author: "LukasAud"
categories:
  - updates
date: "2022-08-26"
blog_tags:
- mysql
- docker
- release
title: "2022-08-26: Content & Tooling Team Status Update"
---

## Take it easy, it's Friday!!

Hey guys, back again with another friday update. As the end of summer starts to approach, we have been busy working on a few important updates. Firstly, as part of our latest maintenance patch, we have made merged
a few important changes on the MySQL and Docker modules and released a new major version for them. Be sure to check them out!

We also want to take this chance to remind the community that our team is moving away from the MODULES project and, as such, any (new or old) issues or bug reports with our modules should be raised in GitHub at the 
appropriate section. This helps us keep better track of our current workload and be more efficient around the issue resolution area.

## Community Contributions

We'd like to thank the following people in the Puppet Community for their contributions over this past week:

- [`puppetlabs-apache#2289`][puppetlabs-apache-pr-2289]: "Add support for all proxy schemes, not just https://", thanks to [canth1][canth1] and the following people who helped get it over the line ([ekohl][ekohl])
- [`puppetlabs-postgresql#1363`][puppetlabs-postgresql-pr-1363]: "Fix puppet-strings documentation", thanks to [ekohl][ekohl]
- [`puppetlabs-postgresql#1356`][puppetlabs-postgresql-pr-1356]: "Only require password when used", thanks to [arjenz][arjenz] and the following people who helped get it over the line ([ekohl][ekohl])
- [`puppetlabs-tomcat#491`][puppetlabs-tomcat-pr-491]: "Allow usage of Context/Resources", thanks to [tuxmea][tuxmea]

## New Module / Gem Releases

The following modules were released this week:

- [`puppetlabs-docker`][puppetlabs-docker] (`5.0.0`)
- [`puppetlabs-postgresql`][puppetlabs-postgresql] (`8.2.1`)
- [`puppetlabs-sqlserver`][puppetlabs-sqlserver] (`3.2.0`)
- [`puppetlabs-mysql`][puppetlabs-mysql](`13.0.0`)

  [puppetlabs-docker]: https://github.com/puppetlabs/puppetlabs-docker
  [puppetlabs-postgresql]: https://github.com/puppetlabs/puppetlabs-postgresql
  [puppetlabs-sqlserver]: https://github.com/puppetlabs/puppetlabs-sqlserver
  [puppetlabs-mysql]: https://github.com/puppetlabs/puppetlabs-mysql
  [puppetlabs-apache-pr-2289]: https://github.com/puppetlabs/puppetlabs-apache/pull/2289
  [canth1]: https://github.com/canth1
  [ekohl]: https://github.com/ekohl
  [puppetlabs-postgresql-pr-1363]: https://github.com/puppetlabs/puppetlabs-postgresql/pull/1363
  [puppetlabs-postgresql-pr-1356]: https://github.com/puppetlabs/puppetlabs-postgresql/pull/1356
  [arjenz]: https://github.com/arjenz
  [puppetlabs-tomcat-pr-491]: https://github.com/puppetlabs/puppetlabs-tomcat/pull/491
  [tuxmea]: https://github.com/tuxmea
