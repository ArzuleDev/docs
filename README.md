# Arzule Documentation

This folder contains the source files for [docs.arzule.com](https://docs.arzule.com), built with [Mintlify](https://mintlify.com).

## Local Development

```bash
# Install the Mintlify CLI
npm i -g mint

# Run the docs locally
cd docs
mint dev
```

Open [http://localhost:3000](http://localhost:3000) to preview.

## Deployment

Docs are automatically deployed when changes are pushed to the main branch. The Mintlify GitHub app handles deployment.

## Structure

```
docs/
├── index.mdx              # Homepage
├── quickstart.mdx         # Getting started guide
├── installation.mdx       # SDK installation
├── concepts/              # Core concepts
├── integrations/          # Framework integrations
├── configuration/         # Configuration options
└── sdk/                   # SDK reference
```

## Adding Pages

1. Create a new `.mdx` file in the appropriate directory
2. Add the page to `docs.json` under the appropriate navigation group
3. Run `mint dev` to preview
