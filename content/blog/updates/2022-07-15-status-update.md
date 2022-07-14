---
author: "pmcmaw"
categories:
  - updates
date: "2022-07-15"
blog_tags: null
title: "2022-07-15: Content & Tooling Team Status Update"
---

## Friday again (yay!)

The team are looking forward to summer hours this week to enjoy some of the great weather that has been forecast for the weekend. As always with July a lot of the team are in and out on holidays but there will always be someone around keeping the lights on.

## Support has now officially ended

Please note as of today we no longer support the following modules, for more indepth information [Aaron's blog post](https://pup.pt/cat/blog/posts/2022-06-30-changes-to-supported-modules/): 

* [Helm](https://forge.puppet.com/modules/puppetlabs/helm)
* [Rook](https://forge.puppet.com/modules/puppetlabs/rook)
* [Panos](https://forge.puppet.com/modules/puppetlabs/panos)
* [Cisco-IOS](https://forge.puppet.com/modules/puppetlabs/cisco_ios)
* [Tagmail](https://forge.puppet.com/modules/puppetlabs/tagmail)
* [Vsphere](https://forge.puppet.com/modules/puppetlabs/vsphere)
* [IBM Installation Manager](https://forge.puppet.com/modules/puppetlabs/ibm_installation_manager)
* [Websphere Application Server](https://forge.puppet.com/modules/puppetlabs/websphere_application_server)

## We are now using Github Issues

Dropping in a quick reminder that we have deactivated issue tracking in Jira. The best way to log an issue is now via GitHub issues on the repo that you are having problems with. 
We will respond to all issues as promptly as we can.

## Community Contributions

We'd like to thank the following people in the Puppet Community for their contributions over this past week:

- [`puppetlabs-docker#846`][puppetlabs-docker-pr-846]: "adding optional variable for package_key_check_source to RedHat", thanks to [STaegtmeier][STaegtmeier]
- [`puppetlabs-postgresql#1349`][puppetlabs-postgresql-pr-1349]: "Fix service status detection on Debian-based OSes", thanks to [arjenz][arjenz] and the following people who helped get it over the line ([ekohl][ekohl])
- [`puppetlabs-stdlib#1250`][puppetlabs-stdlib-pr-1250]: "Simplify stdlib::manage", thanks to [jcpunk][jcpunk]
- [`puppetlabs-stdlib#1244`][puppetlabs-stdlib-pr-1244]: "Convert `ensure_packages` to new API and refactor", thanks to [alexjfisher][alexjfisher] and the following people who helped get it over the line ([hlindberg][hlindberg], [ekohl][ekohl])
- [`pdk-templates#474`][pdk-templates-pr-474]: "Adds documentation for testing and mocking facts", thanks to [logicminds][logicminds]

## New Module / Gem Releases

The following modules were released this week:

- [`puppetlabs-stdlib`][puppetlabs-stdlib] (`8.3.0`)

  [puppetlabs-stdlib]: https://github.com/puppetlabs/puppetlabs-stdlib
  [puppetlabs-docker-pr-846]: https://github.com/puppetlabs/puppetlabs-docker/pull/846
  [STaegtmeier]: https://github.com/STaegtmeier
  [puppetlabs-postgresql-pr-1349]: https://github.com/puppetlabs/puppetlabs-postgresql/pull/1349
  [arjenz]: https://github.com/arjenz
  [ekohl]: https://github.com/ekohl
  [puppetlabs-stdlib-pr-1250]: https://github.com/puppetlabs/puppetlabs-stdlib/pull/1250
  [jcpunk]: https://github.com/jcpunk
  [puppetlabs-stdlib-pr-1244]: https://github.com/puppetlabs/puppetlabs-stdlib/pull/1244
  [alexjfisher]: https://github.com/alexjfisher
  [hlindberg]: https://github.com/hlindberg
  [pdk-templates-pr-474]: https://github.com/puppetlabs/pdk-templates/pull/474
  [logicminds]: https://github.com/logicminds
