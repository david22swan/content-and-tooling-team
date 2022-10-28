---
author: "david22swan"
categories:
  - updates
date: "2022-10-28"
blog_tags: null
title: "2022-10-28: Content & Tooling Team Status Update"
---

## Happy Halloween!

Happy Halloween everybody!!!

Hope your all having fun getting dressed up and overdosing on candy, I know we are. Anyway back to the main reason we're here.
It's been a bit of a slow week, lot of holidays have been taken.

## Puppet Strings

The tool puppet-strings has has had some work done to it to fix up a bug and has since been released.

## Continuing Work

A good bit of work is continuing in the background, we are still finishing of some larger projects that have taken a good few weeks to get though or have run into issue's as we went.

## Puppet Approved

We've done a rework of the Puppet approval process for community modules, more information on this can be found [here][puppet-approved] within it's very own blog post.

## Community Contributions

We'd like to thank the following people in the Puppet Community for their contributions over this past week:

- [`puppetlabs-apache#2338`][puppetlabs-apache-pr-2338]: "Make serveradmin an optional parameter and use it", thanks to [ekohl][ekohl]
- [`puppetlabs-apache#2337`][puppetlabs-apache-pr-2337]: "Automatically enable mod_http2 if needed", thanks to [ekohl][ekohl]
- [`puppetlabs-apache#2336`][puppetlabs-apache-pr-2336]: "Update EL8+ and Debian SSL defaults", thanks to [ekohl][ekohl]
- [`puppetlabs-apache#2335`][puppetlabs-apache-pr-2335]: "Support setting SSLProxyCipherSuite on mod_ssl", thanks to [ekohl][ekohl]
- [`puppetlabs-haproxy#526`][puppetlabs-haproxy-pr-526]: "update resolver parameters", thanks to [bugfood][bugfood]
- [`puppetlabs-mysql#1478`][puppetlabs-mysql-pr-1478]: "MySQL 8.0: Grant required privileges to xtrabackup user", thanks to [jan-win1993][jan-win1993]
- [`puppetlabs-vcsrepo#574`][puppetlabs-vcsrepo-pr-574]: "support umask for git repos (try 2)", thanks to [bugfood][bugfood]
- [`puppetlabs_spec_helper#353`][puppetlabs_spec_helper-pr-353]: "Add rspec-github integration", thanks to [ekohl][ekohl]
- [`puppetlabs_spec_helper#346`][puppetlabs_spec_helper-pr-346]: "Fix check:git_ignore rake task for git >= 2.32.0", thanks to [ekohl][ekohl] and the following people who helped get it over the line ([bastelfreak][bastelfreak])

## New Module / Gem Releases

The following modules were released this week:

- [`puppetlabs-docker`][puppetlabs-docker] (`5.1.0`)
- [`puppetlabs-mysql`][puppetlabs-mysql] (`13.0.1`)

  [puppetlabs-docker]: https://github.com/puppetlabs/puppetlabs-docker
  [puppetlabs-mysql]: http://github.com/puppetlabs/puppetlabs-mysql
  [puppetlabs-apache-pr-2338]: https://github.com/puppetlabs/puppetlabs-apache/pull/2338
  [ekohl]: https://github.com/ekohl
  [puppetlabs-apache-pr-2337]: https://github.com/puppetlabs/puppetlabs-apache/pull/2337
  [puppetlabs-apache-pr-2336]: https://github.com/puppetlabs/puppetlabs-apache/pull/2336
  [puppetlabs-apache-pr-2335]: https://github.com/puppetlabs/puppetlabs-apache/pull/2335
  [puppetlabs-haproxy-pr-526]: https://github.com/puppetlabs/puppetlabs-haproxy/pull/526
  [bugfood]: https://github.com/bugfood
  [puppetlabs-mysql-pr-1478]: https://github.com/puppetlabs/puppetlabs-mysql/pull/1478
  [jan-win1993]: https://github.com/jan-win1993
  [puppetlabs-vcsrepo-pr-574]: https://github.com/puppetlabs/puppetlabs-vcsrepo/pull/574
  [puppetlabs_spec_helper-pr-353]: https://github.com/puppetlabs/puppetlabs_spec_helper/pull/353
  [puppetlabs_spec_helper-pr-346]: https://github.com/puppetlabs/puppetlabs_spec_helper/pull/346
  [bastelfreak]: https://github.com/bastelfreak
  [puppet-approved]: https://github.com/puppetlabs/content-and-tooling-team/blob/main/content/blog/posts/2022-10-28-module-approval-process.md
