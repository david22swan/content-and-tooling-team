---
author: "GSPatton"
categories:
  - updates
date: "2022-10-21"
blog_tags: null
title: "2022-10-21: Content & Tooling Team Status Update"
---

## Relax it's Friday!

Hey y'all, it's Friday! That means it's time to reflect on the week just passed. We hope you've had a good week and are looking forward to a well earned rest this weekend.

## puppet-lint 3.0.1 release

[Craig][chelnak] worked with [ekohl][ekohl] to release puppet-lint 3.0.1 which fixed a regression that stopped plugin authors from consuming the spec helpers from puppet-lint. Big thanks to [ekohl][ekohl] for your contributions.

## puppet-lint plugin to check for unsafe interpolations

[I've][GSPatton] continued to work on a plugin for puppet-lint which checks for unsafe interpolations in Puppet code. This piece of work comes as part of our efforts to make writing Puppet code more secure.

## Community Contributions

We'd like to thank the following people in the Puppet Community for their contributions over this past week:

- [`puppetlabs-accounts#426`][puppetlabs-accounts-pr-426]: "Update bash_profile so that it identifies itself as "Puppet Managed"", thanks to [bschonec][bschonec]
- [`puppetlabs-postgresql#1376`][puppetlabs-postgresql-pr-1376]: "pg_hba_rule: Validate userinput in postgresql::server", thanks to [bastelfreak][bastelfreak]
- [`puppetlabs-stdlib#1280`][puppetlabs-stdlib-pr-1280]: "Drop Puppet < 3.6 support in package_provider fact", thanks to [ekohl][ekohl]
- [`puppetlabs-stdlib#1279`][puppetlabs-stdlib-pr-1279]: "Correct bcrypt salt regex", thanks to [sabo][sabo] and the following people who helped get it over the line ([kenyon][kenyon])
- [`puppetlabs-stdlib#1278`][puppetlabs-stdlib-pr-1278]: "Determine root_home without shelling out", thanks to [ekohl][ekohl]
- [`puppet-lint#66`][puppet-lint-pr-66]: "Fix plugin regressions introduced in 3.0.0", thanks to [ekohl][ekohl]
- [`puppetlabs-kubernetes#581`][puppetlabs-kubernetes-pr-581]: "etcd data dir path configurable by hiera", thanks to [metode-cz][metode-cz]

  [puppetlabs-accounts-pr-426]: https://github.com/puppetlabs/puppetlabs-accounts/pull/426
  [bschonec]: https://github.com/bschonec
  [puppetlabs-postgresql-pr-1376]: https://github.com/puppetlabs/puppetlabs-postgresql/pull/1376
  [bastelfreak]: https://github.com/bastelfreak
  [puppetlabs-stdlib-pr-1280]: https://github.com/puppetlabs/puppetlabs-stdlib/pull/1280
  [ekohl]: https://github.com/ekohl
  [puppetlabs-stdlib-pr-1279]: https://github.com/puppetlabs/puppetlabs-stdlib/pull/1279
  [sabo]: https://github.com/sabo
  [kenyon]: https://github.com/kenyon
  [puppetlabs-stdlib-pr-1278]: https://github.com/puppetlabs/puppetlabs-stdlib/pull/1278
  [puppet-lint-pr-66]: https://github.com/puppetlabs/puppet-lint/pull/66
  [puppetlabs-kubernetes-pr-581]: https://github.com/puppetlabs/puppetlabs-kubernetes/pull/581
  [metode-cz]: https://github.com/metode-cz
  [chelnak]: https://github.com/chelnak
  [GSPatton]: https://github.com/GSPatton
