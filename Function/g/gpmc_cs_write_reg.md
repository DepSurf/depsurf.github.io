# Function: <code>gpmc_cs_write_reg</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void gpmc_cs_write_reg(int cs, int idx, u32 val)
```

```json
{
  "name": "gpmc_cs_write_reg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234273472,
      "name": "gpmc_cs_write_reg",
      "external": true,
      "loc": "drivers/memory/omap-gpmc.c:265",
      "file": "drivers/memory/omap-gpmc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context",
        "drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context",
        "drivers/memory/omap-gpmc.c:gpmc_probe",
        "drivers/memory/omap-gpmc.c:gpmc_probe_generic_child",
        "drivers/memory/omap-gpmc.c:gpmc_probe_generic_child",
        "drivers/memory/omap-gpmc.c:gpmc_cs_program_settings",
        "drivers/memory/omap-gpmc.c:gpmc_cs_free",
        "drivers/memory/omap-gpmc.c:gpmc_cs_request",
        "drivers/memory/omap-gpmc.c:gpmc_cs_request",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_memconf",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:gpmc_cs_set_timings",
        "drivers/memory/omap-gpmc.c:set_gpmc_timing_reg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234265240,
      "name": "gpmc_cs_write_reg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void gpmc_cs_write_reg(int cs, int idx, u32 val)
```
</details>
</li>
</ul>
