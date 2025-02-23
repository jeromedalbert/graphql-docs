# graphql-docs Changelog

A concise overview of the public-facing changes to the gem from version to version. Does not include internal changes to the dev experience for the gem.

## Unreleased

## v4.0.0 - 2023-01-26

- **Breaking change**: drop support for Ruby 2.5 and earlier
- CLI with limited options, e.g. `graphql-docs schema.graphql`
- Dart Sass replaces Ruby Sass because Ruby Sass is deprecated
- Fixes:
  - Upgrade commonmarker to latest ver to address security vulnerabilities
  - commonmarker pinned to version without security vulnerability
- Chores
  - Dev env refresh

## v3.0.1 - 2022-10-14

- fix: Relieves `EscapeUtils.escape_html is deprecated. Use GCI.escapeHTML instead, it's faster` deprecation warning until it gets released in an downstream dependency
- meta: Maintainership change from [gjtorikian](https://github.com/gjtorikian) to [brettchalupa](https://github.com/brettchalupa)

## v3.0.0 - 2022-03-23

- Upgrades `graphql` gem to the 2.x series
