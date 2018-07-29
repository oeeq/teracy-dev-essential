# teracy-dev-essential

This is an extension to set up a good enough basic essential dev workstation


## How to use

Configure `workspace/teracy-dev-entry/config_default.yaml` with the following similar content:

```yaml
teracy-dev:
  extensions:
    - _id: "entry-0"
      path: teracy-dev-essential
      require_version: ">= 0.1.0-SNAPSHOT"
      enabled: true
```
