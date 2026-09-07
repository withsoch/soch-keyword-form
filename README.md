Internal SEO keyword submission form for Soch.

Static page. Posts to the `seo-keyword-submit` n8n webhook on sochconsulting.app.n8n.cloud, which kicks off the SEO content pipeline (brief -> article -> images -> Webflow draft).

Passcode-gated (client-side, sha256 in source) and noindex'd. This is a speed bump against drive-by submissions, not real auth.

Source of truth: `web/pages/soch-keyword-submit.html` in the private soch-assistant repo.
