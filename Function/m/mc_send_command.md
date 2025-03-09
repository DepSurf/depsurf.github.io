# Function: <code>mc_send_command</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int mc_send_command(struct fsl_mc_io * mc_io, struct fsl_mc_command * cmd)
```

```json
{
  "name": "mc_send_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496452328,
      "name": "mc_send_command",
      "external": true,
      "loc": "drivers/bus/fsl-mc/mc-sys.c:244",
      "file": "drivers/bus/fsl-mc/mc-sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/fsl-mc/dpbp.c:dpbp_get_attributes",
        "drivers/bus/fsl-mc/dpbp.c:dpbp_reset",
        "drivers/bus/fsl-mc/dpbp.c:dpbp_disable",
        "drivers/bus/fsl-mc/dpbp.c:dpbp_enable",
        "drivers/bus/fsl-mc/dpbp.c:dpbp_close",
        "drivers/bus/fsl-mc/dpbp.c:dpbp_open",
        "drivers/bus/fsl-mc/dpcon.c:dpcon_set_notification",
        "drivers/bus/fsl-mc/dpcon.c:dpcon_get_attributes",
        "drivers/bus/fsl-mc/dpcon.c:dpcon_reset",
        "drivers/bus/fsl-mc/dpcon.c:dpcon_disable",
        "drivers/bus/fsl-mc/dpcon.c:dpcon_enable",
        "drivers/bus/fsl-mc/dpcon.c:dpcon_close",
        "drivers/bus/fsl-mc/dpcon.c:dpcon_open",
        "drivers/bus/fsl-mc/dprc.c:dprc_get_container_id",
        "drivers/bus/fsl-mc/dprc.c:dprc_get_api_version",
        "drivers/bus/fsl-mc/dprc.c:dprc_get_obj_region",
        "drivers/bus/fsl-mc/dprc.c:dprc_set_obj_irq",
        "drivers/bus/fsl-mc/dprc.c:dprc_get_obj",
        "drivers/bus/fsl-mc/dprc.c:dprc_get_obj_count",
        "drivers/bus/fsl-mc/dprc.c:dprc_get_attributes",
        "drivers/bus/fsl-mc/dprc.c:dprc_clear_irq_status",
        "drivers/bus/fsl-mc/dprc.c:dprc_get_irq_status",
        "drivers/bus/fsl-mc/dprc.c:dprc_set_irq_mask",
        "drivers/bus/fsl-mc/dprc.c:dprc_set_irq_enable",
        "drivers/bus/fsl-mc/dprc.c:dprc_set_irq",
        "drivers/bus/fsl-mc/dprc.c:dprc_close",
        "drivers/bus/fsl-mc/dprc.c:dprc_open",
        "drivers/bus/fsl-mc/dpmcp.c:dpmcp_reset",
        "drivers/bus/fsl-mc/dpmcp.c:dpmcp_close",
        "drivers/bus/fsl-mc/dpmcp.c:dpmcp_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496452328,
      "name": "mc_send_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int mc_send_command(struct fsl_mc_io * mc_io, struct fsl_mc_command * cmd)
```
</details>
</li>
</ul>
