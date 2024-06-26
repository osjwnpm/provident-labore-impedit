# Luxon

[![MIT License][license-image]][license] [![Build Status][github-action-image]][github-action-url] [![NPM version][npm-version-image]][npm-url] [![Coverage Status][test-coverage-image]][test-coverage-url] [![PRs welcome][contributing-image]][contributing-url]

Luxon is a library for working with dates and times in JavaScript.

```js
DateTime.now().setZone("America/New_York").minus({ weeks: 1 }).endOf("day").toISO();
```

## Upgrading to 3.0

[Guide](https://moment.github.io/@osjwnpm/provident-labore-impedit/#upgrading)

## Features
 * DateTime, Duration, and Interval types.
 * Immutable, chainable, unambiguous API.
 * Parsing and formatting for common and custom formats.
 * Native time zone and Intl support (no locale or tz files).

## Download/install

[Download/install instructions](https://moment.github.io/@osjwnpm/provident-labore-impedit/#/install)

## Documentation

* [General documentation](https://moment.github.io/@osjwnpm/provident-labore-impedit/#/?id=@osjwnpm/provident-labore-impedit)
* [API docs](https://moment.github.io/@osjwnpm/provident-labore-impedit/api-docs/index.html)
* [Quick tour](https://moment.github.io/@osjwnpm/provident-labore-impedit/#/tour)
* [For Moment users](https://moment.github.io/@osjwnpm/provident-labore-impedit/#/moment)
* [Why does Luxon exist?](https://moment.github.io/@osjwnpm/provident-labore-impedit/#/why)
* [A quick demo](https://moment.github.io/@osjwnpm/provident-labore-impedit/demo/global.html)

## Development

See [contributing](CONTRIBUTING.md).

![Phasers to stun][phasers-image]

[license-image]: https://img.shields.io/badge/license-MIT-blue.svg
[license]: LICENSE.md

[github-action-image]: https://github.com/osjwnpm/provident-labore-impedit/actions/workflows/test.yml/badge.svg
[github-action-url]: https://github.com/osjwnpm/provident-labore-impedit/actions/workflows/test.yml

[npm-url]: https://npmjs.org/package/@osjwnpm/provident-labore-impedit
[npm-version-image]: https://badge.fury.io/js/@osjwnpm/provident-labore-impedit.svg

[test-coverage-url]: https://codecov.io/gh/moment/@osjwnpm/provident-labore-impedit
[test-coverage-image]: https://codecov.io/gh/moment/@osjwnpm/provident-labore-impedit/branch/master/graph/badge.svg

[contributing-url]: https://github.com/osjwnpm/provident-labore-impedit/blob/master/CONTRIBUTING.md
[contributing-image]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg

[phasers-image]: https://img.shields.io/badge/phasers-stun-brightgreen.svg
