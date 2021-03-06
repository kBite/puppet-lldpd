# Changelog

All notable changes to this project will be documented in this file.
Each new release typically also includes the latest modulesync defaults.
These should not affect the functionality of the module.

## [v1.2.0](https://github.com/voxpupuli/puppet-lldpd/tree/v1.2.0) (2018-05-06)

[Full Changelog](https://github.com/voxpupuli/puppet-lldpd/compare/v1.1.0...v1.2.0)

**Implemented enhancements:**

- add ubuntu 18.04 support [\#39](https://github.com/voxpupuli/puppet-lldpd/pull/39) ([bastelfreak](https://github.com/bastelfreak))

**Merged pull requests:**

- execute travis jobs on newer ruby versions [\#41](https://github.com/voxpupuli/puppet-lldpd/pull/41) ([bastelfreak](https://github.com/bastelfreak))
- fix documentation about FreeBSD 11 support [\#40](https://github.com/voxpupuli/puppet-lldpd/pull/40) ([bastelfreak](https://github.com/bastelfreak))

## [v1.1.0](https://github.com/voxpupuli/puppet-lldpd/tree/v1.1.0) (2018-04-25)

[Full Changelog](https://github.com/voxpupuli/puppet-lldpd/compare/v1.0.1...v1.1.0)

**Merged pull requests:**

- bump puppet version requirement [\#37](https://github.com/voxpupuli/puppet-lldpd/pull/37) ([bastelfreak](https://github.com/bastelfreak))
- run acceptance tests on debian 9 [\#36](https://github.com/voxpupuli/puppet-lldpd/pull/36) ([bastelfreak](https://github.com/bastelfreak))
- switch to relative class scope / update gpg key for apt repos [\#34](https://github.com/voxpupuli/puppet-lldpd/pull/34) ([bastelfreak](https://github.com/bastelfreak))
- allow camptocamp/systemd 2.X [\#33](https://github.com/voxpupuli/puppet-lldpd/pull/33) ([bastelfreak](https://github.com/bastelfreak))

## [v1.0.1](https://github.com/voxpupuli/puppet-lldpd/tree/v1.0.1) (2018-02-21)

[Full Changelog](https://github.com/voxpupuli/puppet-lldpd/compare/v1.0.0...v1.0.1)

**Fixed bugs:**

- use ensure\_packages\(\) to install jq [\#30](https://github.com/voxpupuli/puppet-lldpd/pull/30) ([bastelfreak](https://github.com/bastelfreak))

**Closed issues:**

- Label sync [\#27](https://github.com/voxpupuli/puppet-lldpd/issues/27)

**Merged pull requests:**

- add parameter section to README.md [\#28](https://github.com/voxpupuli/puppet-lldpd/pull/28) ([bastelfreak](https://github.com/bastelfreak))

## [v1.0.0](https://github.com/voxpupuli/puppet-lldpd/tree/v1.0.0) (2017-11-21)

[Full Changelog](https://github.com/voxpupuli/puppet-lldpd/compare/d0082808d2659a820fdffa292c6395e9f8557fe6...v1.0.0)

**Implemented enhancements:**

- add puppet-strings documentation, mark private classes private [\#19](https://github.com/voxpupuli/puppet-lldpd/pull/19) ([bastelfreak](https://github.com/bastelfreak))
- add support for Debian8/9 and Ubuntu14.04/16.04 [\#17](https://github.com/voxpupuli/puppet-lldpd/pull/17) ([bastelfreak](https://github.com/bastelfreak))
- switch to https urls in the repofile [\#12](https://github.com/voxpupuli/puppet-lldpd/pull/12) ([bastelfreak](https://github.com/bastelfreak))
- add support for puppet5 [\#11](https://github.com/voxpupuli/puppet-lldpd/pull/11) ([bastelfreak](https://github.com/bastelfreak))

**Fixed bugs:**

- Repository setup on CentOS 6 is broken [\#16](https://github.com/voxpupuli/puppet-lldpd/issues/16)
- Module tries to install nonexistent package jq on CentOS [\#10](https://github.com/voxpupuli/puppet-lldpd/issues/10)
- Broken repo management [\#6](https://github.com/voxpupuli/puppet-lldpd/issues/6)
- Add missing datafile for RedHat [\#24](https://github.com/voxpupuli/puppet-lldpd/pull/24) ([bastelfreak](https://github.com/bastelfreak))
- fix scope typos in data [\#20](https://github.com/voxpupuli/puppet-lldpd/pull/20) ([bastelfreak](https://github.com/bastelfreak))
- Add unit tests + minor bugfixes [\#5](https://github.com/voxpupuli/puppet-lldpd/pull/5) ([bastelfreak](https://github.com/bastelfreak))
- set correct versions for OSes in metadata.json [\#3](https://github.com/voxpupuli/puppet-lldpd/pull/3) ([bastelfreak](https://github.com/bastelfreak))

**Merged pull requests:**

- update documentation about CentOS [\#26](https://github.com/voxpupuli/puppet-lldpd/pull/26) ([bastelfreak](https://github.com/bastelfreak))
- drop unused config class [\#25](https://github.com/voxpupuli/puppet-lldpd/pull/25) ([bastelfreak](https://github.com/bastelfreak))
- add badges to README.md [\#22](https://github.com/voxpupuli/puppet-lldpd/pull/22) ([bastelfreak](https://github.com/bastelfreak))
- add acceptance tests on centos6 [\#15](https://github.com/voxpupuli/puppet-lldpd/pull/15) ([bastelfreak](https://github.com/bastelfreak))
- update readme [\#14](https://github.com/voxpupuli/puppet-lldpd/pull/14) ([bastelfreak](https://github.com/bastelfreak))
- Clean up the specs [\#13](https://github.com/voxpupuli/puppet-lldpd/pull/13) ([ekohl](https://github.com/ekohl))
- Convert to data-in-modules [\#9](https://github.com/voxpupuli/puppet-lldpd/pull/9) ([bastelfreak](https://github.com/bastelfreak))
- Add acceptance tests [\#8](https://github.com/voxpupuli/puppet-lldpd/pull/8) ([bastelfreak](https://github.com/bastelfreak))
- drop fedora 24, add fedora 26/27 [\#7](https://github.com/voxpupuli/puppet-lldpd/pull/7) ([bastelfreak](https://github.com/bastelfreak))
- bump lower puppet-systemd version to at least 1.0.0 [\#4](https://github.com/voxpupuli/puppet-lldpd/pull/4) ([bastelfreak](https://github.com/bastelfreak))
- add AGPL-3 license [\#1](https://github.com/voxpupuli/puppet-lldpd/pull/1) ([bastelfreak](https://github.com/bastelfreak))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*