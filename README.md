# Unscroll privacy policy site

This directory is a self-contained GitHub Pages publishing package. It is intentionally independent from the Android build and contains no scripts, external assets, analytics, cookies, or network dependencies.

## Browser-only upload

1. Open the separate `unscroll-privacy` repository on GitHub.
2. Upload `index.html` at the publishing source root.
3. Upload the `assets` directory and `assets/unscroll-logo.svg` at the same level as `index.html`.
4. In **Settings → Pages**, choose the approved branch and `/(root)` as the source.
5. Wait for deployment, then verify the exact HTTPS URL on a phone and desktop browser.
6. Only after the URL is approved should it be placed in `SupportContent.PRIVACY_POLICY_URL` and the Android app rebuilt.

## Manual confirmations before publication

- Confirm the policy operator/legal entity, which is intentionally not invented here.
- Confirm the effective date (`25 October 2026`) remains correct at publication.
- Recheck the policy against the release build's permissions and data behavior.
