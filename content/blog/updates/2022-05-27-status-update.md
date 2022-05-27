---
author: "Peter Murphy"
categories:
  - updates
date: "2022-05-27"
blog_tags: null
title: "2022-05-27: Content & Tooling Team Status Update"
---

## Friday Team Roundup

Happy Friday from the CAT team! The team has been up to lots this week and there's much to celebrate 🍾.

[Craig](https://github.com/chelnak) has released PDK `2.5.0` 🎉. With this release, PDK now supports the `SLES 15`
OS. Massive shoutout to Craig for this, it was a lot of work and he's done a fantastic job.

[Lukas](https://github.com/LukasAud) has put out a new release of the [MySQL](https://github.com/puppetlabs/puppetlabs-mysql)
module, we're now at version `12.0.3`. This release includes the return of Debian systems to a functional state along 
with other changes that can be found [here](https://forge.puppet.com/modules/puppetlabs/mysql/12.0.3/changelog).

We've begun work on syntax fixes and restructuring of modules to make sure they abide by community module standards. 
[David](https://github.com/david22swan) has commenced this process on the [apache](https://github.com/puppetlabs/puppetlabs-apache) 
module. As this process is difficult and takes time, David would be grateful to anyone from the community that
would be available to help him. Please feel free to message David Swan on the Puppet Community Slack channel.
Additionally, it is imperative going forth that community module PRs and syntax stricty abide by community standards
and conventions.

I ([Peter](https://github.com/petergmurphy)) have continued work on minor bug fixes and enhancements for 
[PRM](https://github.com/puppetlabs/prm). There will be a minor version release coming to PRM next week.

## Community Contributions

We'd like to thank the following people in the Puppet Community for their contributions over this past week:

- [`device_manager#86`][device_manager-pr-86]: "Update for Puppet 7 compability", thanks to [tkishel][tkishel] and the following people who helped get it over the line ([bastelfreak][bastelfreak])
- [`puppetlabs-apache#2238`][puppetlabs-apache-pr-2238]: "Drop support for Fedora < 18", thanks to [ekohl][ekohl]
- [`puppetlabs-apache#2222`][puppetlabs-apache-pr-2222]: "apache::vhost ProxyPassMatch in Location containers", thanks to [skylar2-uw][skylar2-uw]
- [`puppetlabs-inifile#457`][puppetlabs-inifile-pr-457]: "match section names containing prefix character (normally [)", thanks to [tja523][tja523] and the following people who helped get it over the line ([daianamezdrea][daianamezdrea])
- [`puppetlabs-java_ks#399`][puppetlabs-java_ks-pr-399]: "Don't require certificate or private key params when ensure: absent", thanks to [tparkercbn][tparkercbn]
- [`puppetlabs-postgresql#1332`][puppetlabs-postgresql-pr-1332]: "README.md: correct postgresql_conn_validator example", thanks to [bastelfreak][bastelfreak] and the following people who helped get it over the line ([ekohl][ekohl], [kenyon][kenyon])

## New Module / Gem Releases

The following modules were released this week:

- [`puppetlabs-inifile`][puppetlabs-inifile] (`5.3.0`)
- [`puppetlabs-mysql`][puppetlabs-mysql] (`12.0.3`)
- [`puppetlabs-acl`][puppetlabs-acl] (`4.1.0`)

  [puppetlabs-inifile]: https://github.com/puppetlabs/puppetlabs-inifile
  [puppetlabs-mysql]: http://github.com/puppetlabs/puppetlabs-mysql
  [puppetlabs-acl]: https://github.com/puppetlabs/puppetlabs-acl
  [device_manager-pr-86]: https://github.com/puppetlabs/device_manager/pull/86
  [tkishel]: https://github.com/tkishel
  [bastelfreak]: https://github.com/bastelfreak
  [puppetlabs-apache-pr-2238]: https://github.com/puppetlabs/puppetlabs-apache/pull/2238
  [ekohl]: https://github.com/ekohl
  [puppetlabs-apache-pr-2222]: https://github.com/puppetlabs/puppetlabs-apache/pull/2222
  [skylar2-uw]: https://github.com/skylar2-uw
  [puppetlabs-inifile-pr-457]: https://github.com/puppetlabs/puppetlabs-inifile/pull/457
  [tja523]: https://github.com/tja523
  [daianamezdrea]: https://github.com/daianamezdrea
  [puppetlabs-java_ks-pr-399]: https://github.com/puppetlabs/puppetlabs-java_ks/pull/399
  [tparkercbn]: https://github.com/tparkercbn
  [puppetlabs-postgresql-pr-1332]: https://github.com/puppetlabs/puppetlabs-postgresql/pull/1332
  [kenyon]: https://github.com/kenyon
