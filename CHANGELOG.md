# Changelog

## [v1.6.0](https://github.com/voxpupuli/puppet-lint-param-docs/tree/v1.6.0) (2020-10-05)

[Full Changelog](https://github.com/voxpupuli/puppet-lint-param-docs/compare/v1.5.1...v1.6.0)

**Implemented enhancements:**

- Warn if parameters that don't exist are documented [\#20](https://github.com/voxpupuli/puppet-lint-param-docs/pull/20) ([alexjfisher](https://github.com/alexjfisher))
- Warn if a parameter is documented more than once and remove support for multi-line \(`/\* \*/`\) comments [\#19](https://github.com/voxpupuli/puppet-lint-param-docs/pull/19) ([alexjfisher](https://github.com/alexjfisher))

**Fixed bugs:**

- Don't warn if name/title are documented in defines [\#22](https://github.com/voxpupuli/puppet-lint-param-docs/pull/22) ([alexjfisher](https://github.com/alexjfisher))

**Merged pull requests:**

- Use absolute parameter name in warnings [\#23](https://github.com/voxpupuli/puppet-lint-param-docs/pull/23) ([alexjfisher](https://github.com/alexjfisher))
- Only release on Ruby 2.6 Travis workers [\#15](https://github.com/voxpupuli/puppet-lint-param-docs/pull/15) ([ekohl](https://github.com/ekohl))

## [v1.5.1](https://github.com/voxpupuli/puppet-lint-param-docs/tree/v1.5.1) (2020-06-23)

[Full Changelog](https://github.com/voxpupuli/puppet-lint-param-docs/compare/v1.5.0...v1.5.1)

**Fixed bugs:**

- Support function calls in param defaults [\#12](https://github.com/voxpupuli/puppet-lint-param-docs/pull/12) ([ekohl](https://github.com/ekohl))

**Merged pull requests:**

- Test multiple Ruby versions + add GHCG [\#13](https://github.com/voxpupuli/puppet-lint-param-docs/pull/13) ([ekohl](https://github.com/ekohl))

## [v1.5.0](https://github.com/voxpupuli/puppet-lint-param-docs/tree/v1.5.0) (2019-01-11)

[Full Changelog](https://github.com/voxpupuli/puppet-lint-param-docs/compare/v1.4.2...v1.5.0)

**Merged pull requests:**

- Whitelist private APIs [\#11](https://github.com/voxpupuli/puppet-lint-param-docs/pull/11) ([ekohl](https://github.com/ekohl))
- Add simplecov as a dev dependency [\#10](https://github.com/voxpupuli/puppet-lint-param-docs/pull/10) ([ekohl](https://github.com/ekohl))

## [v1.4.2](https://github.com/voxpupuli/puppet-lint-param-docs/tree/v1.4.2) (2017-03-29)

[Full Changelog](https://github.com/voxpupuli/puppet-lint-param-docs/compare/v1.4.1...v1.4.2)

**Closed issues:**

- Missing dependency for spec tests. [\#9](https://github.com/voxpupuli/puppet-lint-param-docs/issues/9)

**Merged pull requests:**

- Allow multiline Puppet Strings documentation of parameters. [\#8](https://github.com/voxpupuli/puppet-lint-param-docs/pull/8) ([irgeek](https://github.com/irgeek))
- Parse YARD parameter docs with type [\#7](https://github.com/voxpupuli/puppet-lint-param-docs/pull/7) ([domcleal](https://github.com/domcleal))

## [v1.4.1](https://github.com/voxpupuli/puppet-lint-param-docs/tree/v1.4.1) (2016-06-22)

[Full Changelog](https://github.com/voxpupuli/puppet-lint-param-docs/compare/v1.4.0...v1.4.1)

## [v1.4.0](https://github.com/voxpupuli/puppet-lint-param-docs/tree/v1.4.0) (2016-03-18)

[Full Changelog](https://github.com/voxpupuli/puppet-lint-param-docs/compare/v1.3.1...v1.4.0)

**Merged pull requests:**

- Add support for new \(puppet-strings\) rdoc @param parameters [\#6](https://github.com/voxpupuli/puppet-lint-param-docs/pull/6) ([vStone](https://github.com/vStone))

## [v1.3.1](https://github.com/voxpupuli/puppet-lint-param-docs/tree/v1.3.1) (2015-09-02)

[Full Changelog](https://github.com/voxpupuli/puppet-lint-param-docs/compare/v1.3.0...v1.3.1)

## [v1.3.0](https://github.com/voxpupuli/puppet-lint-param-docs/tree/v1.3.0) (2015-07-24)

[Full Changelog](https://github.com/voxpupuli/puppet-lint-param-docs/compare/v1.2.0...v1.3.0)

## [v1.2.0](https://github.com/voxpupuli/puppet-lint-param-docs/tree/v1.2.0) (2015-06-25)

[Full Changelog](https://github.com/voxpupuli/puppet-lint-param-docs/compare/v1.1.0...v1.2.0)

**Merged pull requests:**

- Expand check to handle defined types as well [\#5](https://github.com/voxpupuli/puppet-lint-param-docs/pull/5) ([irgeek](https://github.com/irgeek))

## [v1.1.0](https://github.com/voxpupuli/puppet-lint-param-docs/tree/v1.1.0) (2014-11-13)

[Full Changelog](https://github.com/voxpupuli/puppet-lint-param-docs/compare/v1.0.1...v1.1.0)

**Merged pull requests:**

- Add Puppet Doc Style check [\#4](https://github.com/voxpupuli/puppet-lint-param-docs/pull/4) ([strider](https://github.com/strider))
- Update README.md [\#2](https://github.com/voxpupuli/puppet-lint-param-docs/pull/2) ([deanwilson](https://github.com/deanwilson))

## [v1.0.1](https://github.com/voxpupuli/puppet-lint-param-docs/tree/v1.0.1) (2014-09-23)

[Full Changelog](https://github.com/voxpupuli/puppet-lint-param-docs/compare/v1.0.0...v1.0.1)

## [v1.0.0](https://github.com/voxpupuli/puppet-lint-param-docs/tree/v1.0.0) (2014-09-23)

[Full Changelog](https://github.com/voxpupuli/puppet-lint-param-docs/compare/8009750386fc1a1b9ab53331d5d42e1c6c45a979...v1.0.0)

**Fixed bugs:**

- Problems reported for unparameterised classes with function calls [\#1](https://github.com/voxpupuli/puppet-lint-param-docs/issues/1)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
