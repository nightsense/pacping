# pacping
Compare response times of Arch Linux mirrors.

## usage

`pacping [country code] [protocol] [ipv]`

examples:
- `pacping all http 4` will compare http/ipv4 servers in all countries
- `pacping IS https 6` will compare https/ipv6 servers in Iceland

## country code

[country code] may be set to:
- `all` (to compare mirrors across the world)
- a specific two-letter country code (to compare mirrors within a single country).

Run `pacping --country-codes` for an up-to-date list of countries hosting Arch mirrors, along with their country codes.

## protocol

[protocol] may be set to `http` or `https`.

## ipv

[ipv] may be set to `4` or `6`.
