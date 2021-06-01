# Renovate configuration

This repository contains common [renovate](https://docs.renovatebot.com/) bot configuration.

Renovate allow to create [presets](https://docs.renovatebot.com/config-presets/) and use them or 
extends them in an other configuration.

## Usage

create a `renovate.json` file in at the root of your repository with this content:

```json
{
  "extends": [
    "github>openfun/renovate-configuration"
  ],
}
```

If you need to extends this preset, you can do it in your config file like explain
in the [preset](https://docs.renovatebot.com/config-presets/) documentation.
