# Ruby standards

Ruby is fortunate to have some well-curated standards documents:

* Bozhidar Batsov’s [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide)
* Bozhidar Batsov’s [Rails Style Guide](https://github.com/bbatsov/rails-style-guide)

Please refer to the above as a baseline when writing Ruby and Rails code
and follow [Sandi Metz’ rules for Developers](http://robots.thoughtbot.com/sandi-metz-rules-for-developers)
to the best of your ability.

## Rails

* Do not use the Rails Asset Pipeline:
  it’s more trouble than it’s worth.
  Instead, use [gulp.js](http://gulpjs.com/) to compile your assets.

## Tooling

* Lint all ruby code with [rubocop](https://github.com/bbatsov/rubocop)
