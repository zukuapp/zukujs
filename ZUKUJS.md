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

# ZukuJS27.0.0

ZukuJS is ZUKU's maintained Next.js derivative. This fork starts from upstream
v16.4.0-canary.58, commit1bcedb48d95a5a9ba6ad77dd2d8ba9ecc4159ba6.
Upstream copyright and the MIT license remain applicable. ZukuJS's command
registry and server protocol are maintained separately by ZUKU.

The upstream package version and import names remain intact for compiler and
adapter compatibility. The product identity is declared by zukujs-version.json
and embedded as package.json.zukujs in the pinned runtime distribution. Browser
branding is not a security boundary and does not conceal identifiable RSC or
framework behavior from a determined client.

The navigation patch publishes completed navigation state before advancing the
action queue. Equivalent compiled ESM and CJS changes are integrity-reviewed in
the parent vendor/next/fork-manifest.json; builds fail on an unexpected version or
router structure. Refresh, discarded actions, and promise ordering remain intact.
