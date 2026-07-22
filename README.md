# Cologra site (GitHub Pages)

Static pages served at https://cologra.vortas.io — landing, privacy policy, support.
Source of truth lives in the main app repo at `site/`; the public `lithsec/cologra-site`
repo is the deploy target (GitHub Pages requires a public repo on the free plan).

Deploy: copy `site/` contents into cologra-site, commit, push. Keep the Next.js
`/privacy` and `/support` pages (apps/web) in sync when editing — same wording.
