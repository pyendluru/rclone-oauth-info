# rclone personal OAuth website

This folder contains the public homepage and privacy policy for a private,
single-user rclone OAuth application.

## Public URLs

- Homepage: `https://rclone.pavithra.net/`
- Privacy policy: `https://rclone.pavithra.net/privacy.html`

## Publishing

These files are published from the root of the public GitHub repository named
`rclone-oauth-info`. The `rclone.pavithra.net` DNS name must be a CNAME pointing
to `pyendluru.github.io`.

Never add the Google OAuth client secret, OAuth tokens, or `rclone.conf` to
this repository.
