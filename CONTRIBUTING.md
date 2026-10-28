Contributing
============

The https://www.ruby-grape.org site is work of [many contributors](https://github.com/ruby-grape/ruby-grape.github.io/graphs/contributors). You're encouraged to submit [pull requests](https://github.com/ruby-grape/ruby-grape.github.io/pulls) and [propose topics](https://github.com/ruby-grape/ruby-grape.github.io/issues). Ask Grape usage questions in the [Grape issue tracker](https://github.com/ruby-grape/grape/issues); website issues belong in this repository.

#### Fork the Project

Fork the [project on Github](https://github.com/ruby-grape/ruby-grape.github.io) and check out your copy.

```
git clone https://github.com/contributor/ruby-grape.github.io.git
cd ruby-grape.github.io
git remote add upstream https://github.com/ruby-grape/ruby-grape.github.io.git
```

#### Create a Topic Branch

Make sure your fork is up-to-date and create a topic branch for your feature or bug fix.

```
git checkout master
git pull upstream master
git checkout -b my-feature-branch
```

#### Bundle Install and Run Jekyll

Use Ruby 3.3 or newer and the committed GitHub Pages-compatible bundle. Ensure that the production site builds before submitting a pull request.

```
bundle install
JEKYLL_ENV=production bundle exec jekyll build --strict_front_matter
bundle exec jekyll serve
```

Navigate to http://localhost:4000.

#### Add Content

Create markdown content.

#### Maintain Releases and Project Listings

Update versions and the verification date in `_data/releases.yml` using [RubyGems](https://rubygems.org/gems/grape/versions). Confirm that each versioned README or upgrade-guide tag exists. The default branch may describe an unreleased version; do not advertise that as a published release. Keep current, previous, and legacy release lines distinct without implying identical support policies.

List only non-archived projects with recent substantive maintenance. Inspect default-branch commits, compatibility work, releases, and runnable setup instructions rather than relying on repository metadata timestamps or an isolated automated workflow bump. Apply the same standard to third-party integrations and examples, retain canonical repository links, and let each project define its own supported versions.

Keep historical talks and tutorials clearly labeled rather than presenting them as current setup guidance. Preserve existing page paths and the `CNAME` custom domain. Keep Markdown paragraphs on one line.

#### Commit Changes

Make sure git knows your name and email address:

```
git config --global user.name "Your Name"
git config --global user.email "contributor@example.com"
```

Writing good commit logs is important. A commit log should describe what you did.

```
git add ...
git commit
```

#### Push

```
git push origin my-feature-branch
```

#### Make a Pull Request

Go to https://github.com/contributor/ruby-grape.github.io and select your feature branch. Click the 'Pull Request' button and fill out the form. Pull requests are usually reviewed within a few days.

#### Rebase

If you've been working on a change for a while, rebase with upstream/master.

```
git fetch upstream
git rebase upstream/master
git push --force-with-lease origin my-feature-branch
```

Keep the pull request focused and never force-push the default branch.

#### Be Patient

It's likely that your change will not be merged and that the nitpicky maintainers will ask you to do more, or fix seemingly benign problems. Hang on there!

#### Thank You

Please do know that we really appreciate and value your time and work. We love you, really.
