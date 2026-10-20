# FilMonitor share preview

Public Open Graph bridge for Telegram link previews at `share.filmonitor.ru`.
It contains no application code or private data and redirects allowed
public-share paths to `filmonitor.ru`.

Portfolio links use a six-character query, for example
`https://share.filmonitor.ru?A1B2C3`. Legacy `?path=/p/...` links remain
supported.

Monitoring links use `?mA1B2C3` and open `/m/i/A1B2C3` on the main site.
Legacy statistics links are supported through an encoded `path` query,
including the original share token and archive filters.
