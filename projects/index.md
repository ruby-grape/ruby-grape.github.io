---
layout: page
title: Community Projects
tags: [projects]
comments: false
---

This directory highlights projects with recent substantive maintenance, reviewed on {{ site.data.releases.checked_on | date: "%B %-d, %Y" }}. Each project defines its own Ruby, Rack, Rails, and Grape compatibility; being listed here does not guarantee support for every current version.

### Core and Community Extensions

| Project | Latest release | Purpose |
|---|---|---|
| [grape](https://github.com/ruby-grape/grape) | [{{ site.data.releases.grape.current }}](https://rubygems.org/gems/grape/versions/{{ site.data.releases.grape.current }}) | Framework for REST-like APIs in Ruby. |
| [grape-entity](https://github.com/ruby-grape/grape-entity) | [{{ site.data.releases.extensions['grape-entity'] }}](https://rubygems.org/gems/grape-entity) | Entity-based API representations. |
| [grape-rabl](https://github.com/ruby-grape/grape-rabl) | [{{ site.data.releases.extensions['grape-rabl'] }}](https://rubygems.org/gems/grape-rabl) | Rabl template rendering. |
| [grape-roar](https://github.com/ruby-grape/grape-roar) | [{{ site.data.releases.extensions['grape-roar'] }}](https://rubygems.org/gems/grape-roar) | Roar representers and HAL responses. |
| [grape-active_model_serializers](https://github.com/ruby-grape/grape-active_model_serializers) | [{{ site.data.releases.extensions['grape-active_model_serializers'] }}](https://rubygems.org/gems/grape-active_model_serializers) | ActiveModelSerializers integration. |
| [grape-swagger](https://github.com/ruby-grape/grape-swagger) | [{{ site.data.releases.extensions['grape-swagger'] }}](https://rubygems.org/gems/grape-swagger) | Swagger/OpenAPI 2.0 documentation generation. |
| [grape-swagger-rails](https://github.com/ruby-grape/grape-swagger-rails) | [{{ site.data.releases.extensions['grape-swagger-rails'] }}](https://rubygems.org/gems/grape-swagger-rails) | Swagger UI packaged as a Rails engine. |
| [grape-swagger-entity](https://github.com/ruby-grape/grape-swagger-entity) | [{{ site.data.releases.extensions['grape-swagger-entity'] }}](https://rubygems.org/gems/grape-swagger-entity) | Schema generation from grape-entity models. |
| [grape-swagger-representable](https://github.com/ruby-grape/grape-swagger-representable) | [{{ site.data.releases.extensions['grape-swagger-representable'] }}](https://rubygems.org/gems/grape-swagger-representable) | Schema generation from Representable models. |

### Maintained Third-Party Projects

| Project | Purpose |
|---|---|
| [otr-activerecord](https://github.com/jhollinger/otr-activerecord) | ActiveRecord setup outside Rails. |
| [api-pagination](https://github.com/davidcelis/api-pagination) | Pagination integration for API applications. |
| [grape-idempotency](https://github.com/jcagarcia/grape-idempotency) | Idempotent request handling. |
| [grape_logging](https://github.com/aserafin/grape_logging) | Request logging and instrumentation. |
| [Skylight](https://github.com/skylightio/skylight-ruby) | Performance monitoring with [Grape integration](https://docs.skylight.io/grape). |
| [grape-starter](https://github.com/LeFnord/grape-starter) | Generate Rack-based Grape API skeletons. |
| [grapethor](https://github.com/rawongithub/grapethor) | Thor-based application, API, and endpoint generators. |

See [maintained example applications](/examples) for complete runnable projects. Archived adapters, dormant integrations, and abandoned generators are not recommended here; historical entries remain available in this site's Git history.

### Contribute

Please [contribute a project](https://github.com/ruby-grape/ruby-grape.github.io/blob/master/CONTRIBUTING.md) to [this page](https://github.com/ruby-grape/ruby-grape.github.io/blob/master/projects/index.md).

Include a short description, canonical repository link, supported versions, and evidence of recent maintenance when proposing an entry. A recent metadata timestamp or automated workflow bump alone is not sufficient.

We welcome maintained ecosystem projects into the [ruby-grape organization](https://github.com/ruby-grape). Propose a transfer in a [website issue](https://github.com/ruby-grape/ruby-grape.github.io/issues) so the maintainers can discuss ownership, releases, and ongoing support.
