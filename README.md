# Seyed Milad Hatamlee — personal website

Academic portfolio built with Jekyll and the Academic Pages theme. Hosted with GitHub Pages.

## Content

- `_pages/about.md`: home page
- `_pages/research.md` and `_pages/research/`: research overview and projects
- `_pages/publications.md`: publication list (the only published `/publications/` page)
- `_pages/teaching.md`: teaching
- `_pages/cv.md` and `files/Hatamlee_CV.pdf`: CV page and downloadable PDF
- `_pages/contact.md`: contact details
- `_data/navigation.yml`: navigation
- `_config.yml`: site URL and profile
- `assets/css/profile.css`: small theme overrides

Template sample pages and collections remain in source but are excluded in `_config.yml`.
Use Jekyll's `relative_url` filter for local links so assets work on both a project path and a custom domain.

## Local build

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

## Custom domain: miladhtml.online

In GitHub Settings → Pages, use the `master` branch and `/ (root)` as the branch publishing source. Set the custom domain to `miladhtml.online`.

For the custom domain, `_config.yml` must use `url: "https://miladhtml.online"` and `baseurl: ""`; the root `CNAME` must contain `miladhtml.online`.

In GoDaddy DNS, configure these website records (default TTL is fine):

| Type | Name | Value |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | miladhtml.github.io |

Replace conflicting website/parking records for `@` and `www`; preserve unrelated email and verification records. Once GitHub validates DNS and provisions the certificate, enable Enforce HTTPS.

Reference: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

Theme attribution and license remain in LICENSE.
