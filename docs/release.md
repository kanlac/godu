# Releasing `godu`

`godu` is released using a GitHub action and `goreleaser`.

1. tag a new version `git tag v1.5.1`
1. push the tag `git push origin v1.5.1`

If everything goes well, that's all you have to do.

## Generate homebrew taps token
Once a year, you need to [generate a new token](https://github.com/settings/tokens?type=beta) for the [homebrew-taps](https://github.com/viktomas/homebrew-taps) repository. So that the `goreleaser` job can write into it.
