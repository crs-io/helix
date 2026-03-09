# Helix

This is a personal fork of [helix-editor/helix](https://github.com/helix-editor/helix). Go use that
repo instead of this one.

## Branches

- `master` tracks upstream's `master` branch.
- `main` is the default branch of this repo; it is `master` plus my own changes.
- All other branches are where I implemented specific features; these should be merged into
  `main` whenever they're done, and hopefully also into `master` if/when accepted by upstream.

## Changes

- [`register_expansion`](https://github.com/crs-io/helix/tree/register_expansion) -- Create a new
  type of expansion (`%reg{}`) which allows for fetching the current contents of a register.
