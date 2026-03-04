# Privacy Policy (Self-Destruct Reading List)

Effective date: 2026-03-04

Self-Destruct Reading List (the “Extension”) helps you save web pages into a reading queue, then automatically moves expired items to a recycle bin (with restore support).

## What data we collect

The Extension does not upload your data to any developer server. To provide its features, it stores the following data locally in your browser:

- Items you save: page title, page URL, saved time, expiry time, and status (queue/done/recycle bin/snoozed, etc.)
- Your settings: default expiry, scan interval, recycle bin retention days, whether self-destruct is paused, etc.
- Local stats: aggregated counts for the “Review” page (e.g. saves, done, restored) over recent days

All of the above is stored locally via `chrome.storage`.

## How we use your data

We use the data only to:

- Display your queue, recycle bin, and review statistics
- Run expiry and clean-up logic (e.g. move expired items to the recycle bin; purge old recycle bin items)
- Apply your settings (e.g. pause self-destruct; scan interval)

## Data sharing and selling

- No sharing: we do not share your data with third parties.
- No selling: we do not sell your data.

## Permissions

The Extension requests the following permissions:

- `storage`: store your items, settings, and stats locally
- `alarms`: schedule periodic expiry scans and clean-up
- `activeTab`: read the current tab’s title/URL when you click the extension button to save
- `contextMenus`: provide “Save page / Save link” actions in the right-click menu

## Data retention and deletion

- You can configure how long items remain in the recycle bin via “Recycle bin retention (days)”.
- You can remove the Extension’s local data via your browser’s extension settings, or uninstall the Extension.

## Children’s privacy

This Extension is not intended for children and does not aim to collect personal identifying information.

## Contact

Please provide a support email/contact method on the Chrome Web Store listing and update it here accordingly.

