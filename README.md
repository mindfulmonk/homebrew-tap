# Introduction

Vault formula that includes a `--with-dynamic` option that allows building vault with `CGO_ENABLED`.
This fixes DNS resolution when on a VPN with Split DNS.

# Install

```
brew tap mindfulmonk/tap
brew install mindfulmonk/tap/vault --with-dynamic
```


# More info

Original implementation https://github.com/Homebrew/homebrew-core/pull/7238
Option removed https://github.com/Homebrew/homebrew-core/issues/33507
Current work on fixing this in Go https://github.com/golang/go/issues/12524
Discourse forum https://discourse.brew.sh/t/vault-dns-resolution-fails-on-vpn-now-that-with-dynamic-is-gone/3913
