# EU CN Code Migration API — Documentation

Public documentation and official **Run in Postman** button for the EU CN Code Migration API, covering indicative Combined Nomenclature code changes from 2026 to 2027.

## Website

After GitHub Pages is enabled for the `main` branch (folder `/ (root)`), the documentation is available at:

https://henrycfg.github.io/eu-cn-code-migration-api-docs/

## API access

Gateway: `https://eu-cn-code-migration-api.p.rapidapi.com`

RapidAPI host header: `eu-cn-code-migration-api.p.rapidapi.com`

Use your own RapidAPI subscription key in the `x-rapidapi-key` header. **Do not commit or publish credentials.**

## Example

`POST /v1/batch/migrate`

```json
{
  "codes": ["02013000", "39076100", "76020011"],
  "from_year": 2026,
  "to_year": 2027
}
```

## Disclaimer

This is an independent, unofficial API. Migration correspondences are indicative, derived from official EU texts, and not guaranteed official equivalences. Some results require manual customs classification review.

## Publishing

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose `main` and `/ (root)`, then **Save**.
4. Open the website and confirm the **Run in Postman** button is visible and functional.
5. Paste the GitHub Pages URL into Postman's **Verify API ownership → Run in Postman button** verification form.

The public page is static HTML and does not require VPS or Nginx changes.
