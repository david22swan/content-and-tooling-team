---
author: "GSPatton"
categories:
  - updates
date: "2022-08-12"
blog_tags: null
title: "2022-08-12: Content & Tooling Team Status Update"
---

## Happy Friday!
Hey! I'm Gavin. I'm new here on the CAT team and have had a very exciting first few weeks getting stuck in. I moved here from the Puppet Comply team working on both the front-end and back-end side of things. Outside of work, I enjoy keeping fit, bouldering, music, reading and spending time with my wife and dog. 

Here are our updates for the week.

After several weeks of work, one of the largest releases we have made has been done for the Apache module.
Containing multiple backwards incompatible updates including the addition of strict data types for each and every type within the module.
As part of this we would like to give a big thanks to both [ekohl][ekohl], [cocker-cc][cocker-cc] and many others for the amount of work they have put into the module over the last few months.

  [ekohl]: https://github.com/ekohl
  [cocker-cc]: https://github.com/cocker-cc

## Community Contributions

We'd like to thank the following people in the Puppet Community for their contributions over this past week:

- [`puppetlabs-apache#2287`][puppetlabs-apache-pr-2287]: "fix duplicate definition of auth_basic-mod", thanks to [sircubbi][sircubbi]
- [`puppetlabs-apache#2284`][puppetlabs-apache-pr-2284]: "Allow custom_config to have a string priority again", thanks to [martin-koerner][martin-koerner]
- [`puppetlabs-apache#2277`][puppetlabs-apache-pr-2277]: "Disable mod_php on EL9", thanks to [ekohl][ekohl]
- [`puppetlabs-apache#2275`][puppetlabs-apache-pr-2275]: "Allow vhosts to have a string priority again", thanks to [ekohl][ekohl]
- [`puppetlabs-apache#2274`][puppetlabs-apache-pr-2274]: "Allow overriding CRS allowed HTTP methods per vhost", thanks to [Vincevrp][Vincevrp]
- [`puppetlabs-apache#2273`][puppetlabs-apache-pr-2273]: "Allow overriding CRS anomaly threshold per vhost", thanks to [Vincevrp][Vincevrp]
- [`puppetlabs-apache#2272`][puppetlabs-apache-pr-2272]: " Allow configuring SecRequestBodyAccess and SecResponseBodyAccess", thanks to [Vincevrp][Vincevrp]
- [`puppetlabs-apache#2271`][puppetlabs-apache-pr-2271]: "Remove duplicate SecDefaultAction in CRS template", thanks to [Vincevrp][Vincevrp]
- [`puppetlabs-apache#2270`][puppetlabs-apache-pr-2270]: "Allow configuring CRS paranoia level", thanks to [Vincevrp][Vincevrp]
- [`puppetlabs-apache#2267`][puppetlabs-apache-pr-2267]: "Drop mod_fastcgi support", thanks to [ekohl][ekohl]
- [`puppetlabs-firewall#1061`][puppetlabs-firewall-pr-1061]: "allow persistence of firewall rules for Suse", thanks to [corporate-gadfly][corporate-gadfly]
- [`puppetlabs-kubernetes#570`][puppetlabs-kubernetes-pr-570]: "Remove empty workflow file", thanks to [deric][deric]
- [`puppetlabs-kubernetes#561`][puppetlabs-kubernetes-pr-561]: "Add proxy support to docker, cri_containerd and kubelet", thanks to [nickperry][nickperry]
- [`puppetlabs-mysql#1481`][puppetlabs-mysql-pr-1481]: "[Compatibility] Add Raspbian OS to provider configuration", thanks to [jordi-upc][jordi-upc]
- [`puppetlabs-mysql#1480`][puppetlabs-mysql-pr-1480]: "Allow excludedatabases when using file_per_database", thanks to [HT43-bqxFqB][HT43-bqxFqB]
- [`puppetlabs-postgresql#1348`][puppetlabs-postgresql-pr-1348]: "Ensure multiple postgresql::server::recovery resources can be defined", thanks to [Deroin][Deroin] and the following people who helped get it over the line ([ekohl][ekohl])
- [`puppetlabs-stdlib#1263`][puppetlabs-stdlib-pr-1263]: "Fix spelling", thanks to [arjenz][arjenz]
- [`puppetlabs-vcsrepo#557`][puppetlabs-vcsrepo-pr-557]: "Add skip_hooks property to vcsrepo ", thanks to [sp-ricard-valverde][sp-ricard-valverde]
- [`litmusimage#44`][litmusimage-pr-44]: "Add CentOS Stream 9 image", thanks to [kajinamit][kajinamit]

## New Module / Gem Releases

The following modules were released this week:

- [`puppetlabs-apt`][puppetlabs-apt] (`8.5.0`)
- [`puppetlabs-java`][puppetlabs-java] (`8.2.0`)
- [`puppetlabs-apache`][puppetlabs-apache] (`8.0.0`)

  [puppetlabs-apt]: https://github.com/puppetlabs/puppetlabs-apt
  [puppetlabs-java]: https://github.com/puppetlabs/puppetlabs-java
  [puppetlabs-apache]: https://github.com/puppetlabs/puppetlabs-apache
  [puppetlabs-apache-pr-2287]: https://github.com/puppetlabs/puppetlabs-apache/pull/2287
  [sircubbi]: https://github.com/sircubbi
  [puppetlabs-apache-pr-2284]: https://github.com/puppetlabs/puppetlabs-apache/pull/2284
  [martin-koerner]: https://github.com/martin-koerner
  [puppetlabs-apache-pr-2277]: https://github.com/puppetlabs/puppetlabs-apache/pull/2277
  [ekohl]: https://github.com/ekohl
  [puppetlabs-apache-pr-2275]: https://github.com/puppetlabs/puppetlabs-apache/pull/2275
  [puppetlabs-apache-pr-2274]: https://github.com/puppetlabs/puppetlabs-apache/pull/2274
  [Vincevrp]: https://github.com/Vincevrp
  [puppetlabs-apache-pr-2273]: https://github.com/puppetlabs/puppetlabs-apache/pull/2273
  [puppetlabs-apache-pr-2272]: https://github.com/puppetlabs/puppetlabs-apache/pull/2272
  [puppetlabs-apache-pr-2271]: https://github.com/puppetlabs/puppetlabs-apache/pull/2271
  [puppetlabs-apache-pr-2270]: https://github.com/puppetlabs/puppetlabs-apache/pull/2270
  [puppetlabs-apache-pr-2267]: https://github.com/puppetlabs/puppetlabs-apache/pull/2267
  [puppetlabs-firewall-pr-1061]: https://github.com/puppetlabs/puppetlabs-firewall/pull/1061
  [corporate-gadfly]: https://github.com/corporate-gadfly
  [puppetlabs-kubernetes-pr-570]: https://github.com/puppetlabs/puppetlabs-kubernetes/pull/570
  [deric]: https://github.com/deric
  [puppetlabs-kubernetes-pr-561]: https://github.com/puppetlabs/puppetlabs-kubernetes/pull/561
  [nickperry]: https://github.com/nickperry
  [puppetlabs-mysql-pr-1481]: https://github.com/puppetlabs/puppetlabs-mysql/pull/1481
  [jordi-upc]: https://github.com/jordi-upc
  [puppetlabs-mysql-pr-1480]: https://github.com/puppetlabs/puppetlabs-mysql/pull/1480
  [HT43-bqxFqB]: https://github.com/HT43-bqxFqB
  [puppetlabs-postgresql-pr-1348]: https://github.com/puppetlabs/puppetlabs-postgresql/pull/1348
  [Deroin]: https://github.com/Deroin
  [puppetlabs-stdlib-pr-1263]: https://github.com/puppetlabs/puppetlabs-stdlib/pull/1263
  [arjenz]: https://github.com/arjenz
  [puppetlabs-vcsrepo-pr-557]: https://github.com/puppetlabs/puppetlabs-vcsrepo/pull/557
  [sp-ricard-valverde]: https://github.com/sp-ricard-valverde
  [litmusimage-pr-44]: https://github.com/puppetlabs/litmusimage/pull/44
  [kajinamit]: https://github.com/kajinamit
