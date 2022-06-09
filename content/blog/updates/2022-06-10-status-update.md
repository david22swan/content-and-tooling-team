---
author: "LukasAud"
categories:
  - updates
date: "2022-06-10"
blog_tags: null
title: "2022-06-10: Content & Tooling Team Status Update"
---

## Yet another friday

Another week, another report. Except its actually been two weeks.  These weeks in Content and Tooling we have worked on:

On community days we have released 11 modules, hitting a new record since the comeback of the CAT team and our weekly blogs.
Soon enough we are expecting all our modules to be up-to-date at the forge with all the upgrades they have been receiving.
But we still have a few bad boys out there that refuse to cooperate.

On the development side of things, our tooling team member has been working on releasing a new version of PRM.
This new 0.2.1 version includes some minor bugfixes and enhacements that aim to increase the QOL of its users.

In addition to this, we have been working on a number of things, from implementing RedHat 9 into our supported modules to
completely rewriting the Apache module syntax, as well as working on several bugfixes for other modules, but those will have
to wait until next week to see the daylight.

Finally, we have reworked some internal documentation to ensure that our team is ready to welcome new members in the future.

That's all for this week, folks! It hasn't been that much of an exciting week but we still have many projects in the drawing board.
Hope you all enjoy your weekend.

## Community Contributions

We'd like to thank the following people in the Puppet Community for their contributions over these past weeks:

- [`puppetlabs-apache#2243`][puppetlabs-apache-pr-2243]: "Acceptance tests: correct EPEL usage", thanks to [ekohl][ekohl]
- [`puppetlabs-apache#2240`][puppetlabs-apache-pr-2240]: "Let limitreqfieldsize and limitreqfields be integers", thanks to [traylenator][traylenator]
- [`puppetlabs-apache#2214`][puppetlabs-apache-pr-2214]: "mod_auth_gssapi: Add support for every configuration directive", thanks to [canth1][canth1]
- [`puppetlabs-docker#834`][puppetlabs-docker-pr-834]: "Update Docker Compose to handle symbols", thanks to [sili72][sili72] and the following people who helped get it over the line ([smortex][smortex], [tuxmea][tuxmea])
- [`puppetlabs-docker#833`][puppetlabs-docker-pr-833]: "Fix docker-compose, network and volumes not applying on 1st run, fix other idempotency", thanks to [canihavethisone][canihavethisone] and the following people who helped get it over the line ([shoddyguard][shoddyguard])
- [`puppetlabs-docker#817`][puppetlabs-docker-pr-817]: "Fixed docker facts to check for active swarm clusters before running docker swarm sub-commands.", thanks to [nmaludy][nmaludy]
- [`puppetlabs-mysql#1476`][puppetlabs-mysql-pr-1476]: "Fix typo in README example", thanks to [rsynnest][rsynnest]
- [`puppetlabs-mysql#1449`][puppetlabs-mysql-pr-1449]: "Use MariaDB for Ubuntu 20.04", thanks to [treydock][treydock] and the following people who helped get it over the line ([ghoneycutt][ghoneycutt], [alexjfisher][alexjfisher])
- [`puppetlabs-mysql#1447`][puppetlabs-mysql-pr-1447]: "Add support for mariabackup ", thanks to [rsynnest][rsynnest]
- [`puppetlabs-postgresql#1326`][puppetlabs-postgresql-pr-1326]: "Use systemctl reload on EL 7 and higher", thanks to [ekohl][ekohl] and the following people who helped get it over the line ([bastelfreak][bastelfreak])
- [`puppetlabs-stdlib#1239`][puppetlabs-stdlib-pr-1239]: "Unbreak `rake strings:generate:reference`", thanks to [smortex][smortex] and the following people who helped get it over the line ([alexjfisher][alexjfisher])
- [`facterdb#253`][facterdb-pr-253]: "add ubuntu/jammy 22.04 facts", thanks to [hbrown-uiowa][hbrown-uiowa]
- [`facterdb#252`][facterdb-pr-252]: "Release 1.18.0", thanks to [bastelfreak][bastelfreak]
- [`facterdb#251`][facterdb-pr-251]: "Add Almalinux 9", thanks to [hbrown-uiowa][hbrown-uiowa]
- [`facterdb#250`][facterdb-pr-250]: "Release 1.17.0", thanks to [bastelfreak][bastelfreak]
- [`facterdb#249`][facterdb-pr-249]: "Add fedora 36 facts", thanks to [hbrown-uiowa][hbrown-uiowa]
- [`puppetlabs_spec_helper#352`][puppetlabs_spec_helper-pr-352]: "Run the `strings:validate:reference` task during `validate`", thanks to [smortex][smortex]

## New Module / Gem Releases

The following modules were released these weeks:

- [`puppetlabs-ntp`][puppetlabs-ntp] (`9.1.1`)
- [`puppetlabs-docker`][puppetlabs-docker] (`4.4.0`)
- [`puppetlabs-apt`][puppetlabs-apt] (`8.4.0`)
- [`puppetlabs-java`][puppetlabs-java] (`8.1.0`)
- [`puppetlabs-java_ks`][puppetlabs-java_ks] (`4.3.1`)
- [`puppetlabs-reboot`][puppetlabs-reboot] (`4.2.0`)
- [`puppetlabs-motd`][puppetlabs-motd] (`6.2.0`)
- [`puppetlabs-registry`][puppetlabs-registry] (`4.1.0`)
- [`puppetlabs-sqlserver`][puppetlabs-sqlserver] (`3.1.0`)
- [`puppetlabs-package`][puppetlabs-package] (`2.2.0`)
- [`puppetlabs-exec`][puppetlabs-exec] (`2.1.0`)

  [puppetlabs-ntp]: https://github.com/puppetlabs/puppetlabs-ntp
  [puppetlabs-docker]: https://github.com/puppetlabs/puppetlabs-docker
  [puppetlabs-apt]: https://github.com/puppetlabs/puppetlabs-apt
  [puppetlabs-java]: https://github.com/puppetlabs/puppetlabs-java
  [puppetlabs-java_ks]: https://github.com/puppetlabs/puppetlabs-java_ks
  [puppetlabs-reboot]: https://github.com/puppetlabs/puppetlabs-reboot
  [puppetlabs-motd]: https://github.com/puppetlabs/puppetlabs-motd
  [puppetlabs-registry]: https://github.com/puppetlabs/puppetlabs-registry
  [puppetlabs-sqlserver]: https://github.com/puppetlabs/puppetlabs-sqlserver
  [puppetlabs-package]: https://github.com/puppetlabs/puppetlabs-package
  [puppetlabs-exec]: https://github.com/puppetlabs/puppetlabs-exec
  [puppetlabs-apache-pr-2243]: https://github.com/puppetlabs/puppetlabs-apache/pull/2243
  [ekohl]: https://github.com/ekohl
  [puppetlabs-apache-pr-2240]: https://github.com/puppetlabs/puppetlabs-apache/pull/2240
  [traylenator]: https://github.com/traylenator
  [puppetlabs-apache-pr-2214]: https://github.com/puppetlabs/puppetlabs-apache/pull/2214
  [canth1]: https://github.com/canth1
  [puppetlabs-docker-pr-834]: https://github.com/puppetlabs/puppetlabs-docker/pull/834
  [sili72]: https://github.com/sili72
  [smortex]: https://github.com/smortex
  [tuxmea]: https://github.com/tuxmea
  [puppetlabs-docker-pr-833]: https://github.com/puppetlabs/puppetlabs-docker/pull/833
  [canihavethisone]: https://github.com/canihavethisone
  [shoddyguard]: https://github.com/shoddyguard
  [puppetlabs-docker-pr-817]: https://github.com/puppetlabs/puppetlabs-docker/pull/817
  [nmaludy]: https://github.com/nmaludy
  [puppetlabs-mysql-pr-1476]: https://github.com/puppetlabs/puppetlabs-mysql/pull/1476
  [rsynnest]: https://github.com/rsynnest
  [puppetlabs-mysql-pr-1449]: https://github.com/puppetlabs/puppetlabs-mysql/pull/1449
  [treydock]: https://github.com/treydock
  [ghoneycutt]: https://github.com/ghoneycutt
  [alexjfisher]: https://github.com/alexjfisher
  [puppetlabs-mysql-pr-1447]: https://github.com/puppetlabs/puppetlabs-mysql/pull/1447
  [puppetlabs-postgresql-pr-1326]: https://github.com/puppetlabs/puppetlabs-postgresql/pull/1326
  [bastelfreak]: https://github.com/bastelfreak
  [puppetlabs-stdlib-pr-1239]: https://github.com/puppetlabs/puppetlabs-stdlib/pull/1239
  [facterdb-pr-253]: https://github.com/voxpupuli/facterdb/pull/253
  [hbrown-uiowa]: https://github.com/hbrown-uiowa
  [facterdb-pr-252]: https://github.com/voxpupuli/facterdb/pull/252
  [facterdb-pr-251]: https://github.com/voxpupuli/facterdb/pull/251
  [facterdb-pr-250]: https://github.com/voxpupuli/facterdb/pull/250
  [facterdb-pr-249]: https://github.com/voxpupuli/facterdb/pull/249
  [puppetlabs_spec_helper-pr-352]: https://github.com/puppetlabs/puppetlabs_spec_helper/pull/352
