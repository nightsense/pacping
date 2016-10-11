# pacping

Compare response times of Arch Linux mirrors.

## Usage

### compare response times of Arch Linux mirrors
pacping COUNTRYCODE PROTOCOL IPV

### list countries (including country codes) that have Arch Linux mirrors
pacping -c

## Details

COUNTRYCODE may be set to 'all' (to compare mirrors worldwide) or a specific
two-letter country code (to compare mirrors within a single country).

PROTOCOL may be set to 'http' or 'https'.

IPV may be set to '4' or '6'.

## Examples

### compare http+ipv4 servers in all countries
pacping all http 4

### compare https+ipv6 servers in Iceland
pacping is https 6
