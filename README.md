# spore-host-plugin-globus

[![Go Report Card](https://goreportcard.com/badge/github.com/scttfrdmn/spore-host-plugin-globus)](https://goreportcard.com/report/github.com/scttfrdmn/spore-host-plugin-globus)
[![codecov](https://codecov.io/gh/scttfrdmn/spore-host-plugin-globus/branch/main/graph/badge.svg)](https://codecov.io/gh/scttfrdmn/spore-host-plugin-globus)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)

Globus Connect Personal plugin for [spore-host](https://github.com/scttfrdmn/spore-host).

```bash
globus login  # one-time

spawn plugin install github:scttfrdmn/spore-host-plugin-globus/globus-connect-personal \
  --instance i-0abc123 \
  --config endpoint_name=my-hpc-endpoint
```
