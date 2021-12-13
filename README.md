# private-github-header

Web Extension to modify the GitHub header for private repos

For people who frequently work in both private and public GitHub repositories,
this provides a clear visual distinction between the two.

**Public repos**:

![Public repos](public.png)

**Private repos**:

![Private repos](private.png)

## Installation

Install from [addons.mozilla.org][amo].

[amo]: https://addons.mozilla.org/en-US/firefox/addon/private-github-header/

## Developing

Use the [`web-ext`](https://github.com/mozilla/web-ext) tool to develop, test,
and build this extension.

```sh
npm install -g web-ext

web-ext run

web-ext lint

web-ext build
```

For now I've been manually uploading the extension to addons.mozilla.org rather
than trying to set up `web-ext sign`.

## Changelog

### 0.1.1 (2021-12-13)

- [bugfix] Update CSS Selector to correctly find label

### 0.1.0 (2020-07-26)

- Initial Release
