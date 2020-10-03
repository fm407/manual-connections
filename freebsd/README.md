# PIA Wireguard for FreeBSD (tested on 12.1)

This scripts require `bash`, `jq` and `wireguard` in order to work, please install the packages before running it. `pkg install bash wireguard jq`

It might happen that the script returns: "The payload_and_signature variable does not contain an OK status.", just re-run the script after `wg-quick down pia`.
