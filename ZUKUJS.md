<!-- BEGIN ZUKU OFFICIAL BRAND -->
<!-- markdownlint-disable MD033 MD041 -->
<p align="center">
  <a href="https://docs.zuzunza.com/">
    <picture>
      <source media="(prefers-color-scheme: dark)"
        srcset="docs/branding/zuku-logo-dark.png">
      <img src="docs/branding/zuku-logo-light.png"
        alt="ZUKU" width="320">
    </picture>
  </a>
</p>
<p align="center">ZUKU - 내가 불러 일으키는 새로운 창작.</p>
<!-- markdownlint-enable MD033 MD041 -->
<!-- END ZUKU OFFICIAL BRAND -->

# ZukuJS

![version](https://img.shields.io/badge/version-v27.26102701-informational)

## Overview

ZukuJS is ZUKU's maintained Next.js derivative.

| Item | Value |
| --- | --- |
| Upstream base | Next.js v16.4.0-canary.58 |
| Upstream commit | `1bcedb48d95a5a9ba6ad77dd2d8ba9ecc4159ba6` |
| Identity manifest | `zukujs-version.json` |
| Command protocol | `zuku-command/1` |

## Identity and compatibility

The package keeps the upstream name `next`, version, and import paths for compiler and adapter compatibility.

## Navigation patch

The navigation patch publishes completed navigation state before it advances the action queue.

## Changelog

See [CHANGELOG.md](CHANGELOG.md).

## License

MIT. See [license.md](license.md).
