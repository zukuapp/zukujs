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

ZukuJS is ZUKU's maintained Next.js derivative. The current release is v27.26102701.

| Item | Value |
| --- | --- |
| Upstream base | Next.js v16.4.0-canary.58 |
| Upstream commit | `1bcedb48d95a5a9ba6ad77dd2d8ba9ecc4159ba6` |
| Identity manifest | `zukujs-version.json` |
| Command protocol | `zuku-command/1` |
| Internal protocol | `zuku-hmac/1` |

Upstream copyright and the MIT license remain applicable. ZUKU maintains the ZukuJS command registry and server protocol separately.

## Identity and compatibility

The upstream package version and import names remain unchanged for compiler and adapter compatibility. `zukujs-version.json` declares the product identity. The pinned runtime distribution embeds it as `package.json.zukujs`. The `version` field in `zukujs-version.json` (`27.0.0`) is not changed by release v27.26102701.

Browser branding is not a security boundary. It does not conceal identifiable RSC or framework behavior from a client.

## Navigation patch

The navigation patch publishes completed navigation state before it advances the action queue. The parent `vendor/next/fork-manifest.json` records integrity reviews of the equivalent compiled ESM and CJS changes. Builds fail on an unexpected version or router structure. Refresh, discarded actions, and promise ordering are unchanged.

## Changelog

See [CHANGELOG.md](CHANGELOG.md).
