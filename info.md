# A Home assistant custom component to get your MNGL gas bill information.

To get started put all the files from`/custom_components/mngl_hass/` here:
`<config directory>/custom_components/mngl_hass/`

**Example configuration.yaml:**

```yaml
sensor:
  - platform: mngl_hass
    mngl_dp_id: 12312321
    scan_interval: 86400
```
