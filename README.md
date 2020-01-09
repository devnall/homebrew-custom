# homebrew-custom

A homebrew tap for my custom formulas, mostly older versions of core formulas.

This is necessary to use in conjunction with the `brew extract` command to
install a version of a package that's older than the current version and that
you didn't previously install/pin.

E.G. I generally need a specific version of Terraform, lest I bump the
statefile to a new version and force everyone else to upgrade.

Honestly, should probably just go download and use the binary for the needed
version outside of homebrew but whatever.
