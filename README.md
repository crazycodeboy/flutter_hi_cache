# flutter_hi_cache

[![pub package](https://img.shields.io/pub/v/flutter_hi_cache.svg)](https://pub.dartlang.org/packages/flutter_hi_cache)
[ ![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg)](https://github.com/crazycodeboy/flutter_hi_cache/pulls)
[ ![flutter_hi_cache release](https://img.shields.io/github/release/crazycodeboy/flutter_hi_cache.svg?maxAge=2592000?style=flat-square)](https://github.com/crazycodeboy/flutter_hi_cache/releases)

A cache manager based on shared_preferences. Works on iOS,Android and Web.

## Content

- [Examples](#examples)
- [Getting started](#getting-started)
- [Contribution](#contribution)

## Examples

* [Examples](https://github.com/crazycodeboy/flutter_hi_cache/tree/master/examples)

## Getting Started

```dart
HiCache.getInstance().setString("cache_ke", "cache_value");
HiCache.getInstance().get("cache_ke");
```

## Contribution

Issues are welcome. Please add a screenshot of you bug and a code snippet. Quickest way to solve issue is to reproduce it in one of the examples.

Pull requests are welcome. If you want to change the API or do something big it is best to create an issue and discuss it first.

---

**[MIT Licensed](https://github.com/crazycodeboy/flutter_hi_cache/blob/master/LICENSE)**
