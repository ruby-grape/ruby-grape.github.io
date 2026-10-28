---
layout: page
title: Examples
tags: [examples]
comments: false
---

These applications have recent maintenance and runnable setup instructions. Check each repository's README and CI matrix for supported versions and required services rather than assuming every example uses the same Ruby, Rack, or Grape release.

### Community Examples

| Example | What it demonstrates |
|---|---|
| [grape-on-rack](https://github.com/ruby-grape/grape-on-rack) | Mount a Grape API on Rack alongside static pages. |
| [grape-on-rails](https://github.com/ruby-grape/grape-on-rails) | Mount a Grape API in Rails. |
| [grape-on-goliath](https://github.com/ruby-grape/grape-on-goliath) | Run Grape behind the Goliath web server. |
| [grape-on-padrino](https://github.com/ruby-grape/grape-on-padrino) | Integrate a Grape API with Padrino. |
| [grape-with-roar](https://github.com/ruby-grape/grape-with-roar) | HAL presenters, JSON writes, and hypermedia clients with Roar. |

#### Grape with Roar: Three Active Variants

* [`master`](https://github.com/ruby-grape/grape-with-roar/tree/master): ActiveModel with generated data and nonpersistent writes.
* [`with-mongoid`](https://github.com/ruby-grape/grape-with-roar/tree/with-mongoid): MongoDB persistence with string IDs and cursor-based pagination.
* [`with-activerecord`](https://github.com/ruby-grape/grape-with-roar/tree/with-activerecord): PostgreSQL persistence with integer IDs and page-based pagination.

### Third-Party Applications

* [grape-api-boilerplate](https://github.com/duffn/grape-api-boilerplate): A maintained application skeleton with ActiveRecord, Swagger documentation, authentication, Docker, and tests.

Older one-off demos and abandoned applications are no longer featured as current starting points. See [resources](/resources) for clearly labeled historical talks and tutorials, or [community projects](/projects) for maintained libraries and generators.

### Contribute

Please [contribute your sample app](https://github.com/ruby-grape/ruby-grape.github.io/blob/master/CONTRIBUTING.md) to [this page](https://github.com/ruby-grape/ruby-grape.github.io/blob/master/examples/index.md).
