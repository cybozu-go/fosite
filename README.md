[![Build Status](https://github.com/canonical/fosite/actions/workflows/test.yml/badge.svg?branch=canonical)](https://github.com/canonical/fosite/actions/workflows/test.yml/badge.svg?branch=canonical)

This is a fork of [Ory Fosite](https://github.com/ory/fosite). The reason for
forking fosite is that we needed to support the
[OAuth 2.0 Device Authorization Grant](https://datatracker.ietf.org/doc/html/rfc8628).
Some work was already done on upstream fosite, but the PRs were never merged.
Our implementation is heavily influnced by the work done on
https://github.com/ory/fosite/pull/701 from:

- [supercairos](https://github.com/supercairos)
- [BuzzBumbleBee](https://github.com/BuzzBumbleBee)

For more information behind our reasoning look at the
[Canonical Hydra fork](https://github.com/canonical/hydra).
