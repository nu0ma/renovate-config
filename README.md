# Renovate Config

Shared Renovate Bot Config Preset

## Usage

Add the following to your `renovate.json` file:

```jsonc
{
    "extends": ["github>nu0ma/renovate-config"],

    // or
    "extends": ["gitlab>nu0ma/renovate-config:no-group"],

    // override any settings here
    "automerge": true
}
```