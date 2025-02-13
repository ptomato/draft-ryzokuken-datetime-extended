# Date and Time on the Internet: Timestamps with additional information

This repository contains a WIP IETF I-D that seeks to replace [RFC 3339](https://tools.ietf.org/html/rfc3339)
by allowing additional information like the timezone and calendar to be specified at the end of the timestamp.

## View

You can view the built HTML version of the draft [here](https://ryzokuken.dev/draft-ryzokuken-datetime-extended/documents/rfc-3339.html).

## Compare

You can compare the differences from the base RFC 3339 [here](https://github.com/ryzokuken/draft-ryzokuken-datetime-extended/compare/original...master).

## Status

- [X] `00-front-area.adoc`
- [X] `01-intro.adoc`
- [ ] `02-definitions.adoc`
- [X] `03-two-digit-years.adoc`
- [X] `04-local-time.adoc`
- [X] `05-date-time-format.adoc`
- [ ] `06-references.adoc`
- [X] `07-security.adoc`
- [ ] `aa-iso-8601.adoc`
- [X] `ab-day-week.adoc`
- [X] `ac-leap-years.adoc`
- [X] `ad-leap-seconds.adoc`

## Building

```shell
$ make clean all
```
