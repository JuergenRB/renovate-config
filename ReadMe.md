# renovate-config

Renovate shareable configuration presets

Renovate's ["config presets"](https://docs.renovatebot.com/config-presets/) are a convenient way to distribute config for reuse across multiple repositories. It is similar in design to ESLint's shareable configs, and can be used for whole repository configs and for individual rules.

Renovate always uses the config from and process only the repository's default branch. ([see](https://docs.renovatebot.com/configuration-options/#basebranches))

## Usage

```JSON
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [ "github>JuergenRB/renovate-config" ]
}
```

Resolves as `https://github.com/JuergenRB/renovate-config` and filename `default.json`.
