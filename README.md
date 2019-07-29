# PreQL Standard Types Library

* Author: Jonathan M. Wilbur <[jonathan@wilbur.space](mailto:jonathan@wilbur.space)>
* Copyright Year: 2019
* License: [MIT License](https://mit-license.org/)

This is currently in development.

## To Do

- [ ] Types
  - [ ] `id`?
  - [x] `boolean`
  - [x] `sint8`
  - [x] `sint16`
  - [x] `sint32`
  - [x] `sint64`
  - [x] `uint8`
  - [x] `uint16`
  - [x] `uint32`
  - [x] `uint64`
  - [x] ~~sreal8~~
  - [x] `sreal16`
  - [x] `sreal32`
  - [x] `sreal64`
  - [x] ~~ureal8~~
  - [x] `ureal16`
  - [x] `ureal32`
  - [x] `ureal64`
  - [x] `varchar8`
  - [x] `varchar16`
  - [x] `varchar32`
  - [x] `varchar64`
  - [x] `text8`
  - [x] `text16`
  - [x] `text32`
  - [x] `text64`
  - [x] `blob8`
  - [x] `blob16`
  - [x] `blob32`
  - [x] `blob64`
  - [x] `personName`
  - [x] `phone`
  - [x] `email`
  - [x] `fqdn`
  - [x] `dnsLabel`
  - [x] `uuid`
  - [x] `oid`
  - [x] `bsonId`
  - [ ] `usZip5`
  - [ ] `usZip9`
  - [ ] `handle` (Twitter, Gab, Discord)
  - [x] `sex`
  - [ ] `timeZone`
  - [ ] `ean` / `upc`
  - [ ] `gtin`
  - [ ] `ssn`
  - [ ] `mac`
  - [ ] `eui`
  - [ ] `oui`
  - [x] `ipv4`
  - [x] `ipv6`
  - [x] `ip`
  - [x] `money`
  - [ ] `iso3166-1`
  - [ ] `iso639`?
  - [x] `date`
  - [x] `time`
  - [x] `datetime`
  - [ ] `timestamp`?
  - [x] `year`
  - [x] `month`
  - [x] `day`
  - [x] `hour`
  - [x] `minute`
  - [x] `second`
  - [x] `millisecond`
  - [ ] Spatial types?
  - [x] `locale`
  - [ ] `mimeType`
  - [x] `uri`
  - [x] `urn`
  - [x] `url`
  - [ ] `urlSchema`
  - [ ] `urlUsername`
  - [ ] `urlPassword`
  - [ ] `urlPath`
  - [ ] `urlQuery`
  - [ ] `urlFragment`
  - [x] `iri`
  - [ ] `irn`
  - [x] `irl`
  - [ ] `irlSchema`
  - [ ] `irlUsername`
  - [ ] `irlPassword`
  - [ ] `irlPath`
  - [ ] `irlQuery`
  - [ ] `irlFragment`
  - [ ] `unc`
  - [ ] `geoCode`
  - [ ] `unixInterfaceName`
  - [ ] `unixFileName`
  - [ ] `unixPath`
  - [ ] `windowsFileName`
  - [ ] `windowsPath`
  - [x] `sid`
  - [ ] `dn`
  - [ ] `rdn`
  - [ ] `dnsRecordType`
  - [x] `compass4` (N, E, S, W)
  - [x] `compass8` (N, NE, E, etc.)
  - [x] `compass16` (N, NNE, ENE, etc.)
  - [x] `latitude`
  - [x] `longitude`
  - [ ] `fahrenheit`
  - [ ] `celcius` (Minimum -273.15)
  - [ ] `kelvins`
  - [x] `element`
  - [ ] `iupacName`
  - [ ] `chemicalFormula`
  - [ ] `doi`
  - [ ] `isbn`
  - [ ] `ticker`
  - [ ] `tlsCipher`
  - [ ] Hashes
    - [ ] `md5`
    - [ ] `sha128`
    - [ ] `sha256`
    - [ ] `sha384`
    - [ ] `sha512`
  - [x] `html`
  - [x] `xml`
  - [x] `json`
  - [x] `yaml`
  - [x] `toml`
  - [ ] `httpCode`
  - [ ] `ftpCode`
  - [ ] `smtpCode`
  - [ ] `pixelColor`
  - [ ] `printerColor`
  - [ ] `leftRight`
  - [ ] `upDown`
  - [ ] `direction4`
  - [ ] `password`
  - [ ] `key`
- [ ] Add LDAP matching rules
- [ ] Add `minimum` and `maximum` to floating point types.
  - [ ] How will the targe libraries ignore storage extrema?
- [ ] Add length indicators to the end of LDAP syntaxes
- [ ] Add these labels:
  - [ ] Theoretical minimum storage in bytes
  - [ ] Theoretical maximum storage in bytes
- [ ] Review backslashes use in regex patterns.
- [ ] Review use of DirectoryString in `openldap` target.
- [ ] Add .NET Class label.
- [ ] Add `units` label
- [ ] Add `unitsSymbol` label
- [ ] Add `mathematicalSymbol` label
- [ ] Add `alert` label
- [ ] Add `operatingSystem` label
- [ ] Add hash security-related label
- [ ] Add `deprecated` label
- [ ] Create Secure-Text type
  - [ ] Filter out SQL injection
  - [ ] Filter out XSS tags
  - [ ] Filter out nulls
  - [ ] Filter out LDAP injection
  - [ ] Filter out Directory Traversal