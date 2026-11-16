# renovate-config

Organization-inherited Renovate config for `cyberuni`.

`org-inherited-config.json` makes every repo in the org extend `github>repobuddy/renovate-preset`, so no repo needs its own `renovate.json` to get the shared policy. A repo can still override it with its own config, for example `{"enabled": false}`.

This works with the Mend-hosted Renovate app. See [Mend-hosted app config](https://docs.renovatebot.com/mend-hosted/hosted-apps-config/).
