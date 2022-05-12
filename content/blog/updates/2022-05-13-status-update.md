---
author: "LukasAud"
categories:
  - updates
date: "2022-05-13"
blog_tags:
- status
- update
- may
- community
- kubernetes
title: "2022-05-13: Content & Tooling Team Status Update"
---

## This week...

We have been busy working on a number of items, from internal tools that our team uses on a regular basis to work more efficiently, to the module side where we are constantly keeping an eye to make sure everything
works the way its supposed to.

On the tooling half of our workload, our engineers have been working on further bugfixing our newly released version of PRM, as well as PCT, which was acting up lately. On the other side of the balance, our modules
work has been mostly focused on the re-certification process of Kubernetes and some heavy maintenance work on the mySQL module. Adding to this, some minor changes have also been merged on our Satellite and Apache
modules.

Finally, we are excited to announce the return of community day next week. If you want more information about the topic, check out our latest blogpost: 
https://github.com/puppetlabs/content-and-tooling-team/blob/main/content/blog/posts/2022-05-11-return-of-community-day.md


## Community Contributions

We'd like to thank the following people in the Puppet Community for their contributions over this past week:

- [`puppetlabs-apache#2212`][puppetlabs-apache-pr-2212]: "mod_auth_gssapi: Add support for `GssapiBasicAuth`.", thanks to [olifre][olifre]
- [`puppetlabs-apache#2206`][puppetlabs-apache-pr-2206]: "init.pp: fix typo in purge_vdir documentation", thanks to [kenyon][kenyon]
- [`puppetlabs-chocolatey#270`][puppetlabs-chocolatey-pr-270]: "update holdable feature", thanks to [rico89][rico89]
- [`puppetlabs-haproxy#506`][puppetlabs-haproxy-pr-506]: "[MODULES-11274] Allow usage of parameter manage_config_dir", thanks to [tuxmea][tuxmea]
- [`puppetlabs-kubernetes#542`][puppetlabs-kubernetes-pr-542]: "Fix #541", thanks to [nickperry][nickperry] and the following people who helped get it over the line ([daianamezdrea][daianamezdrea])
- [`puppetlabs-kubernetes#540`][puppetlabs-kubernetes-pr-540]: "Remove cgroup-driver arg to avoid deprecation warnings", thanks to [treydock][treydock]
- [`puppetlabs-stdlib#1241`][puppetlabs-stdlib-pr-1241]: "Update load_module_metadata.rb to correct capitalisation in strings documentartion", thanks to [davidsandilands][davidsandilands]

## New Module / Gem Releases

The following modules were released this week:

  [puppetlabs-apache-pr-2212]: https://github.com/puppetlabs/puppetlabs-apache/pull/2212
  [olifre]: https://github.com/olifre
  [puppetlabs-apache-pr-2206]: https://github.com/puppetlabs/puppetlabs-apache/pull/2206
  [kenyon]: https://github.com/kenyon
  [puppetlabs-chocolatey-pr-270]: https://github.com/puppetlabs/puppetlabs-chocolatey/pull/270
  [rico89]: https://github.com/rico89
  [puppetlabs-haproxy-pr-506]: https://github.com/puppetlabs/puppetlabs-haproxy/pull/506
  [tuxmea]: https://github.com/tuxmea
  [puppetlabs-kubernetes-pr-542]: https://github.com/puppetlabs/puppetlabs-kubernetes/pull/542
  [nickperry]: https://github.com/nickperry
  [daianamezdrea]: https://github.com/daianamezdrea
  [puppetlabs-kubernetes-pr-540]: https://github.com/puppetlabs/puppetlabs-kubernetes/pull/540
  [treydock]: https://github.com/treydock
  [puppetlabs-stdlib-pr-1241]: https://github.com/puppetlabs/puppetlabs-stdlib/pull/1241
  [davidsandilands]: https://github.com/davidsandilands
