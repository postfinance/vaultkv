[![Go Report Card](https://goreportcard.com/badge/github.com/postfinance/vaultkv)](https://goreportcard.com/report/github.com/postfinance/vaultkv)
[![GoDoc](https://godoc.org/github.com/postfinance/vaultkv?status.svg)](https://godoc.org/github.com/postfinance/vaultkv)
[![Build Status](https://github.com/postfinance/vaultkv/workflows/build/badge.svg)](https://github.com/postfinance/vaultkv/actions)
[![Coverage Status](https://coveralls.io/repos/github/postfinance/vaultkv/badge.svg?branch=master)](https://coveralls.io/github/postfinance/vaultkv?branch=master)

# Package vaultkv

Package vaultkv provides version agnostic methods for read, write and list of secrets from @hashicorp Vault's KV secret engines

Replaces: `github.com/postfinance/vault/kv`

## Requirements

Requires list and read privileges on `/sys/mounts`
