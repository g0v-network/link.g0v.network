# Shortlinks: `link.g0v.network`

This code repository contains a list of helpful shortlinks for finding public resources.

The shortlinks are automatically updated on each change to this repository

[![screencast of shortlinks in action](http://g.recordit.co/tcG9ky2XQz.gif)](https://recordit.co/tcG9ky2XQz)

## Why?

Maintaining a shortlink service with other people allows:
1. Building a common language of keywords, helpful for voice communication and finding the digital resources themselves,
2. Updating shortlink keywords allows resources to be migrated without requiring everyone to be notified.

| Workflow | Status |
|----------|--------|
| :gear: [`update-shortlinks`][] | :scroll: [![Shortlink Badge][shortlink-badge]][shortlink-logs]

[`update-shortlinks`]: /.github/workflows/update-shortlinks.yml
[shortlink-badge]: https://github.com/g0v-network/link.g0v.network/actions/workflows/update-shortlinks.yml/badge.svg
[shortlink-logs]: https://github.com/g0v-network/link.g0v.networ/actions/workflows/update-shortlinks.yml

DNS records for this shortlink service are managed in a collectively-run code repository, [`link.g0v.network/domains`][g0v-domains]. You can view the specific config file for this subdomain at: [`link.g0v.network/dns`][dns]

   [dns]: https://link.g0v.network/dns
   [g0v-domains]: https://link.g0v.network/domains/

## Technologies Used

- **Python.** A programming langauge common in scripting.
- [**`spreadsheet2shortlinks`**][spreadsheet2shortlinks]. Command-line tool for updating Rebrandly shortlinks from a spreadsheet.
- [**GitHub Actions.**][github-actions] A script-running service that runs scheduled tasks for us in the cloud. (Incoming)
- [**Rebrandly.**][rebrandly] Hosted service for managing short, descriptive links with a custom domain. (free tier: 200 links)

[spreadsheet2shortlinks]: https://github.com/hyphacoop/spreadsheet2shortlinks
[github-actions]: https://github.com/features/actions
[rebrandly]: https://support.rebrandly.com/hc/en-us/articles/223459547-What-is-Rebrandly-

## Prior Art

- [`hyphacoop/worker-coop-scripts`](https://github.com/hyphacoop/worker-coop-scripts)
- [`CivicTechTO/civictechto-scripts`](https://github.com/CivicTechTO/civictechto-scripts)
- [`patcon/go.talent.c4nada.ca`](https://github.com/patcon/go.talent.c4nada.ca)
