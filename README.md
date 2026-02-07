# Urtentic Documentation

Product documentation for Urtentic's identity verification platform, built with [Mintlify](https://mintlify.com).

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```
npm i -g mint
```

Run the following command at the root of the documentation directory:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Structure

- `docs.json` - Mintlify configuration (navigation, branding, OpenAPI)
- `index.mdx` - Welcome page
- `getting-started.mdx` - Quickstart guide
- `key-concepts.mdx` - Platform terminology
- `verification-processes/` - Document verification, liveness, location, email, video agreement, AML/watchlist
- `webhooks/` - Webhook overview, configuration, workflow management, integration guide
- `sdk/` - Web SDK and Direct Link integration
- `api-reference/` - API introduction and OpenAPI spec

## Publishing

Changes pushed to the default branch are deployed automatically via the Mintlify GitHub app.
