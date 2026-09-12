# Verbi invite page

Served at <https://theverbiapp.github.io/i/> — an invite link looks like
`https://theverbiapp.github.io/i/?c=AB2CDE`.

**Do not edit `index.html` here.** The source of truth is `web/invite/index.html`
in the Verbi app repo, where the page's copy is checked against the App Review
3.1.1 vocabulary list on every build. Edit it there and run
`./web/invite/deploy.sh`.

The page makes no network requests of any kind and never checks whether a code
is real — it is the only unauthenticated surface in the invite feature, and a
page that answered "does this code exist?" would be a code-checking oracle.
