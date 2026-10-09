---
layout: default
---

# Feature

This user script helps you to:

* skip countdown ads or continue pages.
* prevent ad pop-up windows.

It **CANNOT** help you to solve reCAPTCHAs.

**Lite edition** removes image-hosting site support from **Full edition**.
If you prefer to use other userscripts to deal with image-hosting sites, you can use the Lite edition.

Any feature request or bug report is welcome.
You could use [GitHub] to report issues or send pull requests.

You could configure some function in [this page][1], please see [here][5] if you
need more information.

# Nightly Builds

Nightly builds are generated automatically from every commit to the `master`
branch, so they include the latest site fixes before the next release.
They are not reviewed as a release and **may break things**.
If something goes wrong, please report it on [GitHub] with the nightly version
number.

* A nightly build replaces the release build in your userscript manager, as
  they share the same name.
* Once installed, it keeps updating from the nightly channel, even after a new
  release is published.
* Its version looks like `X.Y.Z.YYYYMMDD.HHMMSS`, which is newer than the
  `X.Y.Z` release it is based on.
  To go back to release builds, uninstall the nightly build first, then install
  the release build.

# Supported Platforms

Please check [this page][2] to see if your browser/userscript manager is
supported.

# Supported Sites

{% for site in site.data.sites -%}
* {{ site }}
{% endfor %}

# Contributors

Forked from [RedirectionHelper] written by [SuYS], and many thanks to our
[contributors](https://github.com/adsbypasser/adsbypasser/graphs/contributors).


[1]: https://adsbypasser.github.io/configure.html
[2]: https://github.com/adsbypasser/adsbypasser/wiki/Supported-Platforms
[5]: https://github.com/adsbypasser/adsbypasser/wiki/Runtime-Configurations
[RedirectionHelper]: https://userscripts-mirror.org/scripts/show/69797
[SuYS]: https://userscripts-mirror.org/users/SuYS.html
[GitHub]: https://github.com/adsbypasser/adsbypasser
