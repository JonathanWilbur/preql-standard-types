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
  - [x] `hostname`
  - [x] `uuid`
  - [x] `oid`
  - [x] `bsonId`
  - [x] `handle` (Twitter, Gab, Discord)
  - [x] `sex`
  - [x] `timeZone`
  - [x] `ean2`
  - [x] `ean5`
  - [x] `ean8`
  - [x] `ean13`
  - [x] `upca`
  - [x] `upcb`
  - [x] `upcc`
  - [x] `upcd`
  - [x] `upce`
  - [x] `upc2`
  - [x] `upc5`
  - [x] `gtin8`
  - [x] `gtin12`
  - [x] `gtin13`
  - [x] `gtin14`
  - [x] `ssn`
  - [x] `eui48`
  - [x] `eui60`
  - [x] `eui64`
  - [x] `cdi32`
  - [x] `cdi40`
  - [x] `oui24`
  - [x] `oui36`
  - [x] `ipv4`
  - [x] `ipv6`
  - [x] `ip`
  - [x] `money`
  - [x] `iso3166-1-alpha-2`
  - [x] `iso3166-1-alpha-3`
  - [x] `iso3166-1-numeric`
  - [x] `iso3166-2`
  - [x] `iso639-1`
  - [x] `iso639-2`
  - [x] `iso639-3`
  - [x] `iso639-5`
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
  - [x] `mimeType`
  - [x] `uri`
  - [x] `urn`
  - [x] `url`
  - [x] ~~`urlSchema`~~ (Same thing as the `irlSchema`.)
  - [ ] `urlUsername`
  - [ ] `urlPassword`
  - [ ] `urlPath`
  - [ ] `urlQuery`
  - [ ] `urlFragment`
  - [x] `iri`
  - [ ] `irn`
  - [x] `irl`
  - [x] `irlSchema`
  - [ ] `irlUsername`
  - [ ] `irlPassword`
  - [ ] `irlPath` (Check for leading "/"?)
  - [ ] `irlQuery` (Check for leading "?"?)
  - [ ] `irlFragment` (Check for leading "#"?)
  - [x] `unc`
  - [x] `plusCode`
  - [x] `unixFileName`
  - [x] `unixPath`
  - [x] `windowsFileName`
  - [x] `windowsPath`
  - [x] `sid`
  - [x] `dn`
  - [x] `rdn`
  - [x] `dnsRecordType`
  - [x] `compass4` (N, E, S, W)
  - [x] `compass8` (N, NE, E, etc.)
  - [x] `compass16` (N, NNE, ENE, etc.)
  - [x] `latitude`
  - [x] `longitude`
  - [x] `fahrenheit` (Minimum -459.67)
  - [x] `celcius` (Minimum -273.15)
  - [x] ~~kelvins~~ (This is simply an unsigned floating-point type.)
  - [ ] Chemistry
    - [x] `element`
    - [ ] `iupacName`
    - [ ] `chemicalFormula`
    - [ ] `casNumber`
    - [ ] `bilsteinReference`
    - [ ] `chebi`
    - [ ] `chembl`
    - [ ] `chemspider`
    - [ ] `echaInfoCard`
    - [ ] `ecNumber`
    - [ ] `gmelinReference`
    - [ ] `kegg`
    - [ ] `mesh`
    - [ ] `pubChemCID`
    - [ ] `unNumber`
    - [ ] `compToxDashboard`
    - [ ] `smiles`
  - [x] `doi`
  - [ ] ISO International Identifiers (Remove dashes and spaces for each)
    - [x] `isbn` (13-digits)
    - [x] `issn` (8-digits) (`^[0-9]{4}-[0-9]{3}[0-9xX]$`)
    - [x] `ismn` (13-digits)
    - [x] `isan` (12 bytes)
    - [ ] `iswc` ("T", then 10 digits)
    - [ ] `istc` (?)
    - [ ] `isrc` (CC-999-YY-NNNNN)
    - [ ] `iswn` (?)
    - [ ] `isin` (12 alphanums)
    - [ ] `iin` (6 digits)
    - [ ] `bei` (unclear)
    - [ ] `lei` (20-character, alpha-numeric code)
    - [ ] `iban` (`CCKK-[0-9A-Z]{1,30}`)
    - [ ] `isil` (`[A-Z0-9/\-:]{1,16}`)
    - [ ] `isli` (`ISLI XXXXXX-XXXXX-X`)
    - [ ] `isni` (16 digits and a check character)
    - [ ] `isci` (?)
    - [ ] Maybe add some sort of check-digit functionality?
  - [ ] `lccn` (Library of Congress Control Number?)
  - [ ] `oclc`
  - [ ] `bici`
  - [ ] `sici`
  - [ ] `asin`
  - [ ] `coden`
  - [ ] `ettn`
  - [ ] `estc`
  - [x] `arn`
  - [ ] `iqn` (`iqn.YYYY-MM.wilbur.space(?:targetName)?`)
  - [ ] `ticker`
  - [ ] `airportCode`
  - [ ] `usbNumber` (HHHH:HHHH)
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
  - [x] `pixelColor`
  - [x] `printerColor`
  - [ ] `leftRight`
  - [ ] `upDown`
  - [ ] `frontBack`
  - [ ] `direction4`
  - [ ] `password`
  - [ ] `key`
  - [x] ~~postalCode~~ (This should just be a VARCHAR(16))
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
- [ ] Add `definingOrganization` annotation
- [ ] Create Secure-Text type
  - [ ] Filter out SQL injection
  - [ ] Filter out XSS tags
  - [ ] Filter out nulls
  - [ ] Filter out LDAP injection
  - [ ] Filter out Directory Traversal
- [ ] Add the `$` to the end of regexes.
  - I omitted this originally because I have had problems with MariaDB matching
    strings when that is included.
- [ ] Add multiple `exampleValue` fields.