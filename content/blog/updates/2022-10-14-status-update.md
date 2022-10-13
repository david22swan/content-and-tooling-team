---
author: "jordanbreen28"
categories:
  - updates
date: "2022-10-14"
blog_tags: null
title: "2022-10-14: Content & Tooling Team Status Update"
---
Happy Friday!!! Hey guys, back again with another Friday blog post. As we approach the middle of October, we can start to feel a hint of spookiness in the air (👻) with Halloween fast approaching. 
This week, as always, the CAT team have been working hard to get updates merged and releases published.

# Puppet-lint improvements
To kick off, this week our team member [Gavin](https://github.com/GSPatton) has been continuing his great work on the puppet-lint plugin, which will help to detect potential security vulnerabilites in puppet code. Remember to check back for more updates on this!
# Rolling out of new releases - some big changes!
[Craig] (https://github.com/chelnak) has been working behind the scenes to cut new releases for both our [puppet-lint](https://github.com/puppetlabs/puppet-lint) and [puppet-strings](https://github.com/puppetlabs/puppet-strings) repos. Perhaps one of the most important changes to note, is the bumping of the minimum supported Ruby version in both repos to 2.7. Some other important changes included is the refactoring of the repos against a new set of rubocop rules, and some general fixes and improvements. 
# Hacktoberfest
Just another quick reminder, if you are a regular contributor or want to get involved, ensure to sign up to [Hacktoberfest](https://hacktoberfest.com/). Most of our open source repos are participating, for an extended list check out our [Hacktoberfest Dashboard](https://github.com/puppetlabs/community/blob/main/hacktoberfest_dashboard.md).
## Community Contributions

We'd like to thank the following people in the Puppet Community for their contributions over this past week:

- [`puppetlabs-apache#2312`][puppetlabs-apache-pr-2312]: "fix directory empty options if an empty array is being used", thanks to [bovy89][bovy89] and the following people who helped get it over the line ([ekohl][ekohl])
- [`puppetlabs-docker#858`][puppetlabs-docker-pr-858]: "Change `stop_wait_time` value to match Docker default", thanks to [sebcdri][sebcdri]
- [`puppetlabs-docker#851`][puppetlabs-docker-pr-851]: "Add missing extra_systemd_parameters values to docker-run.erb", thanks to [cbowman0][cbowman0]
- [`puppetlabs-firewall#1066`][puppetlabs-firewall-pr-1066]: "Add negate to match_mark", thanks to [Antiarchitect][Antiarchitect]
- [`puppetlabs-postgresql#1375`][puppetlabs-postgresql-pr-1375]: "pg_hba_rule: Move `type` datatype to own type", thanks to [bastelfreak][bastelfreak]
- [`puppetlabs-postgresql#1372`][puppetlabs-postgresql-pr-1372]: "pg_hba_rule does not properly verify address parameter", thanks to [tuxmea][tuxmea] and the following people who helped get it over the line ([ekohl][ekohl], [bastelfreak][bastelfreak])
- [`puppet-resource_api#301`][puppet-resource_api-pr-301]: "(packaging) Bump to version '1.8.17' [no-promote]", thanks to [tvpartytonight][tvpartytonight]
- [`puppet-strings#317`][puppet-strings-pr-317]: "Use tilde heredocs for readability", thanks to [danielparks][danielparks]

## New Module / Gem Releases

The following modules were released this week:

- [`puppetlabs-stdlib`][puppetlabs-stdlib] (`8.5.0`)

  [puppetlabs-stdlib]: https://github.com/puppetlabs/puppetlabs-stdlib
  [puppetlabs-apache-pr-2312]: https://github.com/puppetlabs/puppetlabs-apache/pull/2312
  [bovy89]: https://github.com/bovy89
  [ekohl]: https://github.com/ekohl
  [puppetlabs-docker-pr-858]: https://github.com/puppetlabs/puppetlabs-docker/pull/858
  [sebcdri]: https://github.com/sebcdri
  [puppetlabs-docker-pr-851]: https://github.com/puppetlabs/puppetlabs-docker/pull/851
  [cbowman0]: https://github.com/cbowman0
  [puppetlabs-firewall-pr-1066]: https://github.com/puppetlabs/puppetlabs-firewall/pull/1066
  [Antiarchitect]: https://github.com/Antiarchitect
  [puppetlabs-postgresql-pr-1375]: https://github.com/puppetlabs/puppetlabs-postgresql/pull/1375
  [bastelfreak]: https://github.com/bastelfreak
  [puppetlabs-postgresql-pr-1372]: https://github.com/puppetlabs/puppetlabs-postgresql/pull/1372
  [tuxmea]: https://github.com/tuxmea
  [puppet-resource_api-pr-301]: https://github.com/puppetlabs/puppet-resource_api/pull/301
  [tvpartytonight]: https://github.com/tvpartytonight
  [puppet-strings-pr-317]: https://github.com/puppetlabs/puppet-strings/pull/317
  [danielparks]: https://github.com/danielparks
