# splunk_windows_enrichment

- Converts Hex Process ID to Decimal (For sysmon correlation)
- Enrich LogonType with human friendly message
- Enrich Kerberos `TicketOptions` with human friendly message
- Enrich Kerberos Encryption Types and PreAuth Types
- Enrich a lot of fields that have `%%dddd` values with human friendly message

> All the conversions happen is Search-Time. It doesn't affect Indexed data.

> Depends on [Splunk Add-on for Microsoft Windows](https://splunkbase.splunk.com/app/742)
