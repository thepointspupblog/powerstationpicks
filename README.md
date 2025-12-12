# Best Power Station

Affiliate site for portable power station reviews.

## Setup Steps

1. **Domain (Porkbun):** Purchase domain, add DNS records
2. **GitHub:** Create repo, enable Pages with GitHub Actions
3. **Google Analytics:** Create GA4 property, add ID to hugo.toml
4. **Amazon Associates:** Apply, get tracking ID, update hugo.toml

## Configuration

Edit `hugo.toml`:
- `baseURL` - Your domain
- `amazonTag` - Your Amazon Associates tag
- `googleAnalytics` - Your GA4 measurement ID (G-XXXXXXXXXX)

## Adding Products

Edit `data/products.json`

## Adding Content

- Guides: `content/guides/`
- Comparisons: `content/comparisons/`
- Categories: `content/categories/`

## Local Development

```bash
hugo server -D
```

## Deploy

Push to main branch. GitHub Actions handles the rest.
