# owasp-scan docker action

Scan an endpoint using the Nikto open source scanner

## Inputs

## `host`

**Required** The host that shall be scanned

## Outputs

## `scan_json`

The JSON formatted scan results


## Example usage

uses: glennadjrussell/owasp-scan@v1
with:
  host: X.X.X.X:3000

