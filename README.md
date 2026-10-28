![](images/grape.png)

Jekyll source for [www.ruby-grape.org](https://www.ruby-grape.org), the Grape community website. It highlights released versions, maintained ecosystem projects, and runnable examples.

Release numbers live in `_data/releases.yml` so the homepage, project directory, and documentation links stay consistent. Existing page URLs and the `CNAME` custom domain are preserved.

Use Ruby 3.3 or newer:

```sh
bundle install
JEKYLL_ENV=production bundle exec jekyll build --strict_front_matter
bundle exec jekyll serve
```

Open [localhost:4000](http://localhost:4000). The bundle remains compatible with GitHub Pages' branch-based deployment; pull requests run a production build.

See [CONTRIBUTING](CONTRIBUTING.md) for release verification, project curation, and contribution instructions.
