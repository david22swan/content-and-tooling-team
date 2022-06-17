---
author: "david22swan"
categories:
  - updates
date: "2022-06-17"
blog_tags: null
title: "2022-06-17: Content & Tooling Team Status Update"
---

## We Have a New Member

As a start to this update I would like to officially welcome Claire McDyre to the CAT team!!!

She's taking over as our PM and is certain to have some good ideas on how the team is going to move in the future and I'm sure that all of you are just as interested as we are in seeing them come to fruition.

## VCSRepo

On a more technical side some of you may have noticed that a good amount of work has been put into the VCSRepo module by our own [Craig][craig], who has been working to get it back into a good condition and ensure that once again matches the high standards that we hold.

## Apache

Similar to the news stated above, you may have also noticed a large amount of activity on the Apache module these last few weeks, kicked of by [myself][me] to properly enforce the syntax rules espoused by the community.
Ensuring the removal of any remaining legacy facts and assigning types and descriptions to each and every variable within the module.

This work has been at first assisted and then continued on by several members of the community who have all either helped with corrections or worked to further improve upon the changes made, so to [ekohl][ekohl], [chillenger][chillenger], [traylenator][traylenator] and [cocker-cc][cocker-cc] I would just like to say thank you!

## Redhat Enterprise Linux 9

Finally to round up our technical news I am officially announcing support for Redhat 9 on our Modules.
While there are a few left that still need some love to get the associated PRs merged we are now ready and able to help with any issues that may arise from the OS and our Modules.

## That's All

Anyway, that's everything.

So have a great weekend from everyone here in the CAT team!

## Community Contributions

We'd like to thank the following people in the Puppet Community for their contributions over this past week:

- [`puppetlabs-acl#261`][puppetlabs-acl-pr-261]: "(MODULES-10908) fix noop behavior", thanks to [garrettrowell][garrettrowell]
- [`puppetlabs-haproxy#508`][puppetlabs-haproxy-pr-508]: "Allow specifying mapfile entries to be collected later", thanks to [yakatz][yakatz]
- [`puppetlabs-postgresql#1345`][puppetlabs-postgresql-pr-1345]: "Set version for Fedora 36", thanks to [lweller][lweller] and the following people who helped get it over the line ([ekohl][ekohl])
- [`puppet-lint#40`][puppet-lint-pr-40]: "Add SARIF support", thanks to [shaopeng-gh][shaopeng-gh] and the following people who helped get it over the line ([ekohl][ekohl], [alexjfisher][alexjfisher])

## New Module / Gem Releases

The following modules were released this week:

- [`puppetlabs-powershell`][puppetlabs-powershell] (`5.1.0`)
- [`puppetlabs-haproxy`][puppetlabs-haproxy] (`6.3.0`)

  [puppetlabs-powershell]: https://github.com/puppetlabs/puppetlabs-powershell
  [puppetlabs-haproxy]: https://github.com/puppetlabs/puppetlabs-haproxy
  [puppetlabs-acl-pr-261]: https://github.com/puppetlabs/puppetlabs-acl/pull/261
  [garrettrowell]: https://github.com/garrettrowell
  [puppetlabs-haproxy-pr-508]: https://github.com/puppetlabs/puppetlabs-haproxy/pull/508
  [yakatz]: https://github.com/yakatz
  [puppetlabs-postgresql-pr-1345]: https://github.com/puppetlabs/puppetlabs-postgresql/pull/1345
  [lweller]: https://github.com/lweller
  [ekohl]: https://github.com/ekohl
  [puppet-lint-pr-40]: https://github.com/puppetlabs/puppet-lint/pull/40
  [shaopeng-gh]: https://github.com/shaopeng-gh
  [alexjfisher]: https://github.com/alexjfisher
  [chillenger]: https://github.com/chillinger
  [traylenator]: https://github.com/traylenator
  [cocker-cc]: https://github.com/cocker-cc

  [craig]: https://github.com/chelnak
  [me]: https://github.com/david22swan
