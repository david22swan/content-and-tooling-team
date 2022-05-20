---
author: "chelnak"
categories:
  - updates
date: "2022-05-20"
blog_tags: null
title: "2022-05-20: Content & Tooling Team Status Update"
---

## It's Friday!

What a week! The CAT team have been super busy this week.

At the close of Community Day on Monday we had cut 10 new module releases.
Many of the modules hadn't seen a release since 2021.
I'm hoping to be able to keep this cadence up so that content available on the forge is always nice and fresh ✨. 

A while back we introduced a "stale" bot 🤖. The aim of the bot was to help us keep on top of the vast amount of issues and pull requests we were seeing.
Being a small team means that staying organised is important and the first version of the bot helped us get back up and running.

When the bot started to do it's thing, we received some really good feedback from you and we learnt alot about how the bot was being perceived.
In the spirit of learning and iteration, Lukas has tweaked how the bot will work in the future and once again will observe how useful it is for us and you.

The main changes include a change of wording and how we label issues and pull requests that don't meet the time constraints we've configured.
Additionally we will no longer be auto-closing issues. They will just get labeled so we can pick them up in our filters and give them the attention that they deserve.

In other news, as part of our effords to increase the overall level of quality for our modules, David has begun an effort to better enforce the various syntax standards
that have been driven by the community.

For me the highlight of this week was the successful return of Community Day.
It's refreshing spending time with our amazing community and I'm excited to have the opportunity to do it more often.

Have a great weekend!

![Happy Friday](https://media.giphy.com/media/kyLYXonQYYfwYDIeZl/giphy.gif)


## Community Contributions

We'd like to thank the following people in the Puppet Community for their contributions over this past week:

- [`puppetlabs-accounts#410`][puppetlabs-accounts-pr-410]: "Added new SSH key type.", thanks to [PorkCharsui79][PorkCharsui79]
- [`puppetlabs-docker#823`][puppetlabs-docker-pr-823]: "Add tmpdir option to docker_compose", thanks to [canihavethisone][canihavethisone]
- [`puppetlabs-firewall#1028`][puppetlabs-firewall-pr-1028]: "CentOS Stream 9 Support (should include RHEL9 when that releases)", thanks to [tskirvin][tskirvin]
- [`puppetlabs-java#516`][puppetlabs-java-pr-516]: "feat: added support for aarch64 architecture download", thanks to [0Rick0][0Rick0]
- [`puppetlabs-motd#431`][puppetlabs-motd-pr-431]: "Update motd location for FreeBSD 13 and above", thanks to [Scnaeg][Scnaeg] and the following people who helped get it over the line ([bastelfreak][bastelfreak])
- [`puppetlabs-scheduled_task#207`][puppetlabs-scheduled_task-pr-207]: "Make disable_time_zone_synchronization idempotent", thanks to [omolenkamp][omolenkamp]
- [`puppetlabs-stdlib#1238`][puppetlabs-stdlib-pr-1238]: "Modernize escape functions", thanks to [smortex][smortex]
- [`puppetlabs-stdlib#1237`][puppetlabs-stdlib-pr-1237]: "Convert data to Pcore before serialisation in to_ruby/to_python", thanks to [smortex][smortex]
- [`puppetlabs-stdlib#1236`][puppetlabs-stdlib-pr-1236]: "Add `xml_encode` function", thanks to [alexjfisher][alexjfisher]
- [`puppetlabs-stdlib#1233`][puppetlabs-stdlib-pr-1233]: "MODULES-11309 : convert a string to a resource", thanks to [jcpunk][jcpunk]
- [`pdk-templates#469`][pdk-templates-pr-469]: "(packaging) Enable puppet-lint-plugins also on Windows #468", thanks to [ConradGroth][ConradGroth] and the following people who helped get it over the line ([bastelfreak][bastelfreak])
- [`pdk-templates#462`][pdk-templates-pr-462]: "Update deprecated setting in README.md", thanks to [skoef][skoef]
- [`puppet-syntax#133`][puppet-syntax-pr-133]: "Release 3.2.1", thanks to [bastelfreak][bastelfreak]
- [`puppet-syntax#132`][puppet-syntax-pr-132]: "Add missing `$` in github action", thanks to [bastelfreak][bastelfreak] and the following people who helped get it over the line ([ekohl][ekohl])
- [`puppet-syntax#131`][puppet-syntax-pr-131]: "Release 3.2.0", thanks to [bastelfreak][bastelfreak]

## New Module / Gem Releases

The following modules were released this week:

- [`puppetlabs-stdlib`][puppetlabs-stdlib] (`8.2.0`)
- [`puppetlabs-concat`][puppetlabs-concat] (`7.2.0`)
- [`puppetlabs-docker`][puppetlabs-docker] (`4.3.0`)
- [`puppetlabs-firewall`][puppetlabs-firewall] (`3.5.0`)
- [`puppetlabs-tomcat`][puppetlabs-tomcat] (`6.2.0`)
- [`puppetlabs-chocolatey`][puppetlabs-chocolatey] (`6.2.0`)
- [`puppetlabs-accounts`][puppetlabs-accounts] (`7.2.0`)
- [`puppetlabs-scheduled_task`][puppetlabs-scheduled_task] (`3.1.0`)
- [`puppetlabs-service`][puppetlabs-service] (`2.2.0`)
- [`puppetlabs-puppet_conf`][puppetlabs-puppet_conf] (`1.3.0`)

  [puppetlabs-stdlib]: https://github.com/puppetlabs/puppetlabs-stdlib
  [puppetlabs-concat]: https://github.com/puppetlabs/puppetlabs-concat
  [puppetlabs-docker]: https://github.com/puppetlabs/puppetlabs-docker
  [puppetlabs-firewall]: http://github.com/puppetlabs/puppetlabs-firewall
  [puppetlabs-tomcat]: https://github.com/puppetlabs/puppetlabs-tomcat
  [puppetlabs-chocolatey]: https://github.com/puppetlabs/puppetlabs-chocolatey
  [puppetlabs-accounts]: https://github.com/puppetlabs/puppetlabs-accounts
  [puppetlabs-scheduled_task]: https://github.com/puppetlabs/puppetlabs-scheduled_task
  [puppetlabs-service]: https://github.com/puppetlabs/puppetlabs-service
  [puppetlabs-puppet_conf]: https://github.com/puppetlabs/puppetlabs-puppet_conf
  [puppetlabs-accounts-pr-410]: https://github.com/puppetlabs/puppetlabs-accounts/pull/410
  [PorkCharsui79]: https://github.com/PorkCharsui79
  [puppetlabs-docker-pr-823]: https://github.com/puppetlabs/puppetlabs-docker/pull/823
  [canihavethisone]: https://github.com/canihavethisone
  [puppetlabs-firewall-pr-1028]: https://github.com/puppetlabs/puppetlabs-firewall/pull/1028
  [tskirvin]: https://github.com/tskirvin
  [puppetlabs-java-pr-516]: https://github.com/puppetlabs/puppetlabs-java/pull/516
  [0Rick0]: https://github.com/0Rick0
  [puppetlabs-motd-pr-431]: https://github.com/puppetlabs/puppetlabs-motd/pull/431
  [Scnaeg]: https://github.com/Scnaeg
  [bastelfreak]: https://github.com/bastelfreak
  [puppetlabs-scheduled_task-pr-207]: https://github.com/puppetlabs/puppetlabs-scheduled_task/pull/207
  [omolenkamp]: https://github.com/omolenkamp
  [puppetlabs-stdlib-pr-1238]: https://github.com/puppetlabs/puppetlabs-stdlib/pull/1238
  [smortex]: https://github.com/smortex
  [puppetlabs-stdlib-pr-1237]: https://github.com/puppetlabs/puppetlabs-stdlib/pull/1237
  [puppetlabs-stdlib-pr-1236]: https://github.com/puppetlabs/puppetlabs-stdlib/pull/1236
  [alexjfisher]: https://github.com/alexjfisher
  [puppetlabs-stdlib-pr-1233]: https://github.com/puppetlabs/puppetlabs-stdlib/pull/1233
  [jcpunk]: https://github.com/jcpunk
  [pdk-templates-pr-469]: https://github.com/puppetlabs/pdk-templates/pull/469
  [ConradGroth]: https://github.com/ConradGroth
  [pdk-templates-pr-462]: https://github.com/puppetlabs/pdk-templates/pull/462
  [skoef]: https://github.com/skoef
  [puppet-syntax-pr-133]: https://github.com/voxpupuli/puppet-syntax/pull/133
  [puppet-syntax-pr-132]: https://github.com/voxpupuli/puppet-syntax/pull/132
  [ekohl]: https://github.com/ekohl
  [puppet-syntax-pr-131]: https://github.com/voxpupuli/puppet-syntax/pull/131
