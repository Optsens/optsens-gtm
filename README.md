# OptSens CMP - Google Tag Manager Template

OptSens Consent Management Platform template for Google Tag Manager. It sets Google
Consent Mode v2 defaults, applies region-specific overrides, injects the OptSens
consent banner, and forwards each visitor's consent choices to your Google tags.

## Repository structure

```
optsens-gtm/
├── template.tpl    # the Community Template Gallery tag (INFO, parameters, sandboxed JS, permissions, tests)
├── metadata.yaml   # gallery metadata (homepage, documentation) and version history
├── LICENSE         # Apache 2.0
└── README.md
```

## Features

- Google Consent Mode v2 (all 7 consent types)
- IAB TCF 2.3 support
- CCPA / CPRA compliance
- GPP (Global Privacy Platform)
- Region-specific consent defaults
- URL passthrough and ads data redaction

## Setup

1. In GTM, open **Templates** > **Search Gallery**.
2. Find **OptSens CMP** and add it.
3. Create a new tag using the template.
4. Enter your OptSens **Domain ID** (from the OptSens dashboard Integration page).
5. Set the trigger to **Consent Initialization - All Pages**.

## Documentation

https://docs.optsens.com/docs/install/google-tag-manager

## License

Apache 2.0
