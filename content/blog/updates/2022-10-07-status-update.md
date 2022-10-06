---
author: "pmcmaw"
categories:
  - updates
date: "2022-10-07"
blog_tags: null
title: "2022-10-07: Content & Tooling Team Status Update"
---

# Goodbye to Summer Hours, Hello to Autumn 

This will be our first week working on Friday afternoon following a long stint of well needed Summer Hours thanks to Perforce. Many of the team including [myself][pmcmaw] really enjoyed the more chilled out and shorter Friday afternoons. It gave us additional time to just really appreciate the longer weekend and the bright nights with family and friends. However now that the extended Summer Hours have finished up we will look forward to kicking Autumn leaves, wrapping up warm, drinking hot chocolate and collecting conkers in our local parks.

# Hacktoberfest

Just a reminder, if you are a regular contributor or want to get involved, ensure to sign up to [Hacktoberfest](https://hacktoberfest.com/). Most of our open source repos are participating, for an extended list check out our [Hacktoberfest Dashboard](https://github.com/puppetlabs/community/blob/main/hacktoberfest_dashboard.md).

# Removal of Debian 9 Support

This week [Jordan][Jordan] has been working on removing support for Debian 9 on our supported modules. Most of his PRs have been merged with a few still outstanding but will be merged in the coming days.

# Rolling out the removal of puppet-module-gems

[David][David] has been busy testing out gem configurations to enable us to remove puppet-module-gems from our supported modules. This will then remove ruby version constraints that members of the community have previously faced. With bundler being clever enough to work out dependencies we are all super exicted to welcome this change! 

# Writing more secure code

The team has been made aware of an issue around command injection in 2 of our supported modules. To find out more information check out this article written and publish by [Ben](https://support.puppet.com/hc/en-us/articles/9219296178199-Puppet-response-for-CVEs-in-puppetlabs-apt-and-puppetlabs-mysql-modules). Our team member [Gavin][Gavin] has this week started working on a puppet-lint plugin that will help users detect simple cases of this vulnerbility. Keep your eyes peeled for more information on this in the coming weeks! 

## Community Contributions

We'd like to thank the following people in the Puppet Community for their contributions over this past week:

- [`puppetlabs-stdlib#1267`][puppetlabs-stdlib-pr-1267]: "Add a Stdlib::CreateResources type", thanks to [ekohl][ekohl]

## New Module / Gem Releases

The following modules were released this week:

- [`puppetlabs-concat`][puppetlabs-concat] (`7.3.0`)
- [`puppetlabs-powershell`][puppetlabs-powershell] (`5.2.0`)
- [`puppetlabs-inifile`][puppetlabs-inifile] (`5.4.0`)
- [`puppetlabs-firewall`][puppetlabs-firewall] (`3.6.0`)
- [`puppetlabs-haproxy`][puppetlabs-haproxy] (`6.4.0`)
- [`puppetlabs-java_ks`][puppetlabs-java_ks] (`4.4.0`)
- [`puppetlabs-reboot`][puppetlabs-reboot] (`4.3.0`)
- [`puppetlabs-motd`][puppetlabs-motd] (`6.3.0`)
- [`puppetlabs-registry`][puppetlabs-registry] (`4.1.1`)
- [`puppetlabs-chocolatey`][puppetlabs-chocolatey] (`6.2.1`)
- [`puppetlabs-acl`][puppetlabs-acl] (`4.1.1`)
- [`puppetlabs-accounts`][puppetlabs-accounts] (`7.3.0`)
- [`puppetlabs-scheduled_task`][puppetlabs-scheduled_task] (`3.1.1`)
- [`puppetlabs-iis`][puppetlabs-iis] (`8.1.1`)
- [`puppetlabs-service`][puppetlabs-service] (`2.3.0`)
- [`puppetlabs-puppet_conf`][puppetlabs-puppet_conf] (`1.4.0`)
- [`puppetlabs-package`][puppetlabs-package] (`2.3.0`)
- [`puppetlabs-exec`][puppetlabs-exec] (`2.2.0`)

  [puppetlabs-concat]: https://github.com/puppetlabs/puppetlabs-concat
  [puppetlabs-powershell]: https://github.com/puppetlabs/puppetlabs-powershell
  [puppetlabs-inifile]: https://github.com/puppetlabs/puppetlabs-inifile
  [puppetlabs-firewall]: http://github.com/puppetlabs/puppetlabs-firewall
  [puppetlabs-haproxy]: https://github.com/puppetlabs/puppetlabs-haproxy
  [puppetlabs-java_ks]: https://github.com/puppetlabs/puppetlabs-java_ks
  [puppetlabs-reboot]: https://github.com/puppetlabs/puppetlabs-reboot
  [puppetlabs-motd]: https://github.com/puppetlabs/puppetlabs-motd
  [puppetlabs-registry]: https://github.com/puppetlabs/puppetlabs-registry
  [puppetlabs-chocolatey]: https://github.com/puppetlabs/puppetlabs-chocolatey
  [puppetlabs-acl]: https://github.com/puppetlabs/puppetlabs-acl
  [puppetlabs-accounts]: https://github.com/puppetlabs/puppetlabs-accounts
  [puppetlabs-scheduled_task]: https://github.com/puppetlabs/puppetlabs-scheduled_task
  [puppetlabs-iis]: https://github.com/puppetlabs/puppetlabs-iis
  [puppetlabs-service]: https://github.com/puppetlabs/puppetlabs-service
  [puppetlabs-puppet_conf]: https://github.com/puppetlabs/puppetlabs-puppet_conf
  [puppetlabs-package]: https://github.com/puppetlabs/puppetlabs-package
  [puppetlabs-exec]: https://github.com/puppetlabs/puppetlabs-exec
  [puppetlabs-stdlib-pr-1267]: https://github.com/puppetlabs/puppetlabs-stdlib/pull/1267
  [ekohl]: https://github.com/ekohl
  [Jordan]: https://github.com/jordanbreen28
  [David]: https://github.com/david22swan
  [Gavin]: https://github.com/GSPatton
  [Ben]: https://github.com/binford2k
  [pmcmaw]: https://github.com/pmcmaw

