# voxrox.org

Source of the [voxrox.org](https://voxrox.org) website — the static project
site of VoxRox, served by GitHub Pages with a custom domain (`CNAME`).

## Layout

- Bilingual content: Czech at the root (`/`, `/privacy/`, `/support/`),
  English under `/en/`.
- Shared assets (styles, brand SVG/PNG) live in `assets/`.

## Deployment

Push to `main` deploys via the GitHub Pages workflow
([`.github/workflows/static.yml`](.github/workflows/static.yml)).

## Content sync

The Privacy, Support and Code signing policy pages mirror the canonical
documents in the [TheVoxRox/mail](https://github.com/TheVoxRox/mail) repository
([`PRIVACY.md`](https://github.com/TheVoxRox/mail/blob/main/PRIVACY.md),
[`SECURITY.md`](https://github.com/TheVoxRox/mail/blob/main/SECURITY.md),
[`CODE_SIGNING_POLICY.md`](https://github.com/TheVoxRox/mail/blob/main/CODE_SIGNING_POLICY.md)).
SignPath Foundation, which the code signing policy is written for, requires the
term "Code signing policy" on the home page, so every footer links to it.
When those documents change, update the corresponding pages here.
