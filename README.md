# go-spiffe library
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fdrrt%2Fgo-spiffe.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fdrrt%2Fgo-spiffe?ref=badge_shield)


### Overview

The go-spiffe library provides functionality to parse and verify SPIFFE
identities encoded in X.509 certificates as described in the
[SPIFFE Standards](https://github.com/spiffe/spiffe/tree/master/standards).

#### func GetUrisInSubjectAltName

```go
func GetUrisInSubjectAltName(certificateString string) (uris []string, err error)
```
Parses an X.509 certificate in PEM format and gets the URIs from the Subject
Alternative Name extension.


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fdrrt%2Fgo-spiffe.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fdrrt%2Fgo-spiffe?ref=badge_large)