---
search:
  boost: 0.5
---

# Aliases

## Aliases

Multi-line string with one or more alias commands.

Example:

```yaml
aliases: |
  alias wr copy running-config startup-config
  alias siib show ip interface brief
```

=== "Table"

    | Variable | Type | Required | Default | Value Restrictions | Description |
    | -------- | ---- | -------- | ------- | ------------------ | ----------- |
    | [<samp>aliases</samp>](## "aliases") | String |  |  |  |  |

=== "YAML"

    ```yaml
    aliases: <str>
    ```
