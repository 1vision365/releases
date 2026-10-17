# 1Vision365 Releases

Public OnPrem release packages and download links.

## Release logs

- [BC28](./Release%2028.md)
- [BC27](./Release%2027.md)
- [BC26](./Release%2026.md)

## Latest package

| App Version | BC Version | Package | Date |
|---|---|---|---|
| 28.5.264 | BC 28.5 | [Download](https://github.com/1vision365/releases/raw/main/downloads/bc28/28.5/1Vision365-OnPrem-Apps-BC28.5-28.5.264.zip) | 17/10/2026 |

# Release notes 28.5.264

BC version: **28.5**

[Original GitHub release](https://github.com/1vision365/1vision-appsource/releases/tag/28.5.264)

## Major changes

_No major changes._

## Minor changes

* iotlink: remove leftover debug message in CheckLicenseObject by @1vision365-neo[bot] in https://github.com/1vision365/1vision-appsource/pull/106
* Add IoT-2-PrintVis orphan cleanup and per-physical-device license count by @1vision365-neo[bot] in https://github.com/1vision365/1vision-appsource/pull/107
* ci: re-trigger review bot after xlf-sync push by @1Vision365-PeterTijsma in https://github.com/1vision365/1vision-appsource/pull/108
* ci: auto-translate needs-translation xlf strings via DeepL by @1Vision365-PeterTijsma in https://github.com/1vision365/1vision-appsource/pull/109
* ci: trigger xlf-sync directly instead of relying on workflow_run by @1Vision365-PeterTijsma in https://github.com/1vision365/1vision-appsource/pull/110
* fix: repair corrupted YAML in xlf-sync.yml (DEEPL_API_KEY expression) by @1Vision365-PeterTijsma in https://github.com/1vision365/1vision-appsource/pull/111
* fix: throttle + retry DeepL calls in xlf-sync to avoid 429 cascades by @1Vision365-PeterTijsma in https://github.com/1vision365/1vision-appsource/pull/112
* ci: allow PR builds on integration/* branches by @1Vision365-PeterTijsma in https://github.com/1vision365/1vision-appsource/pull/114
* feat(iot2printvis): quantity registration per operation type (issue #30) by @1vision365-neo[bot] in https://github.com/1vision365/1vision-appsource/pull/136
* xlf-sync: sync translations on the integration branch after merge instead of on every PR branch by @1Vision365-PeterTijsma in https://github.com/1vision365/1vision-appsource/pull/139
* fix(tests): LicenseCount-tests meten fysieke apparaten direct (CheckLicense is een no-op onder testrunner) by @1Vision365-PeterTijsma in https://github.com/1vision365/1vision-appsource/pull/140
* xlf-sync: ????n run per PR, UTF-8 fix (mojibake) + herstel, overzichtsmail als tabel by @1Vision365-PeterTijsma in https://github.com/1vision365/1vision-appsource/pull/141
* xlf-sync mail: geen lege tabellen na de cap, href via HtmlEncode by @1Vision365-PeterTijsma in https://github.com/1vision365/1vision-appsource/pull/142
* Fix unaccounted idle time filter to match all flagged reasons (WI #146) by @1vision365-neo[bot] in https://github.com/1vision365/1vision-appsource/pull/149
* Fix #143: guard FindFirst crash in Idle Time Reg OnValidate by @1vision365-neo[bot] in https://github.com/1vision365/1vision-appsource/pull/148
* Add action to copy IoT Device Type and Controller Adapter to selected records by @1vision365-neo[bot] in https://github.com/1vision365/1vision-appsource/pull/150
* Fix #154: restore ID scope in idle-time overlap filter (downtime not appearing in consumption log) by @1vision365-neo[bot] in https://github.com/1vision365/1vision-appsource/pull/155
* Fix caption typos and improve generic tooltips (#152) by @1vision365-neo[bot] in https://github.com/1vision365/1vision-appsource/pull/156
* Fix #143 follow-up: disable automatic TableRelation check on Section Code / Idle Type by @1vision365-neo[bot] in https://github.com/1vision365/1vision-appsource/pull/157



