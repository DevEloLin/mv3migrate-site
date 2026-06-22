# mv3migrate-site

Public website and issue entrypoint for `mv3migrate`.

This repository is the official public-facing site. It does **not** contain the
private CLI source code.

## What lives here

- The landing page at `https://mv3migrate.elolin.com/`
- Pricing and purchase guidance
- How-it-works documentation
- FAQ and public validation claims
- The issue tracker for the public site and product feedback

## What does not live here

- The private CLI source tree
- Vendor-only release scripts
- Local keys or internal fixtures

## Issue submission

Use GitHub Issues for product or site feedback:

- https://github.com/DevEloLin/mv3migrate-site/issues

Use the public contact email for direct sales or license questions:

- `mv3migrate@elolin.com`

## Purchase flow

1. Open the Pricing page.
2. Click the email purchase link.
3. Receive a signed license token by email.
4. Run the CLI locally with `--license` and `--license-public-key`.
5. Validate the output in Chrome and keep the report / patch.

## Usage model

The product is local-first:

- Free users can run the first-pass conversion and report generation locally.
- Pro buyers can unlock batch runs, premium DNR drafts, and patch export.
- The CLI does not require a hosted account for normal use.

## Official links

- Site: https://mv3migrate.elolin.com/
- Issues: https://github.com/DevEloLin/mv3migrate-site/issues
- Contact: `mv3migrate@elolin.com`

