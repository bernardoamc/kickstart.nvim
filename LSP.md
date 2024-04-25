# Required LSPs

These should be installed in order for the LSPs to be loaded correctly.

## Ruby LSP

Install [ruby-lsp](https://github.com/Shopify/ruby-lsp).

`gem install ruby-lsp`

Remember that this will install the gem only for the current Ruby version.

## Go

Install `Go`.

Add to your bash config:

```sh
# go configuration
export GOPATH=$HOME/go
export PATH="$GOPATH/bin:$PATH"
```

