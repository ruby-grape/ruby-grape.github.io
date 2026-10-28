---
layout: default
comments: false
---

## Build APIs with Grape

Grape is a REST-like API framework for Ruby. Build Rack applications or mount an API alongside Rails and other frameworks, with a DSL for routing, parameters, validation, versioning, and content negotiation.

## Latest Releases

Stable releases verified against RubyGems on {{ site.data.releases.checked_on | date: "%B %-d, %Y" }}:

| Release line | Latest version | Minimum Ruby | Documentation |
|---|---|---|---|
| Current: 4.x | [{{ site.data.releases.grape.current }}](https://rubygems.org/gems/grape/versions/{{ site.data.releases.grape.current }}) | 3.3 | [Released README](https://github.com/ruby-grape/grape/blob/v{{ site.data.releases.grape.current }}/README.md) |
| Previous: 3.x | [{{ site.data.releases.grape.previous }}](https://rubygems.org/gems/grape/versions/{{ site.data.releases.grape.previous }}) | 3.3 | [Released README](https://github.com/ruby-grape/grape/blob/v{{ site.data.releases.grape.previous }}/README.md) |
| Legacy: 2.x | [{{ site.data.releases.grape.legacy }}](https://rubygems.org/gems/grape/versions/{{ site.data.releases.grape.legacy }}) | 2.7 | [Released README](https://github.com/ruby-grape/grape/blob/v{{ site.data.releases.grape.legacy }}/README.md) |

Start new applications with the current release. Previous and legacy versions are listed for existing applications, not as a promise of ongoing support. Consult the released README and [upgrade guide](https://github.com/ruby-grape/grape/blob/v{{ site.data.releases.grape.current }}/UPGRADING.md) for compatibility and breaking changes; the default branch can document unreleased work.

```sh
bundle add grape --version '~> 4.0'
```

## Explore the Ecosystem

* [Community projects](/projects): Maintained libraries for serialization, documentation, data access, and more, with current extension releases.
* [Examples](/examples): Actively maintained Rack, Rails, Goliath, Padrino, and HAL applications.
* [Resources](/resources): Released documentation, API reference, upgrade guidance, and historical talks.
* [Users](/users): Community-reported adoption, including historical examples.
* [History, team, and contributing](/team): How Grape is maintained and how to get involved.

## Get Help and Contribute

Use the [Grape issue tracker](https://github.com/ruby-grape/grape/issues) for questions and bug reports. For an extension or example, open an issue in its own repository. Contributions are welcome; see [Grape's contribution guide](https://github.com/ruby-grape/grape/blob/master/CONTRIBUTING.md) and our [code of conduct](/code_of_conduct).
