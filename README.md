# MTA-STS policy for droneclub.ee

Served by GitHub Pages at https://mta-sts.droneclub.ee/.well-known/mta-sts.txt.
Tells other mail servers to use encrypted (TLS) delivery to Google (smtp.google.com).
Mode is `testing` (reports only). Change to `enforce` once TLS reports are clean, and bump the `id` in the `_mta-sts.droneclub.ee` TXT record whenever this file changes.
