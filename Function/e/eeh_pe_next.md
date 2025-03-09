# Function: <code>eeh_pe_next</code>

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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct eeh_pe * eeh_pe_next(struct eeh_pe * pe, struct eeh_pe * root)
```

```json
{
  "name": "eeh_pe_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282457908,
      "name": "eeh_pe_next",
      "external": true,
      "loc": "arch/powerpc/kernel/eeh_pe.c:182",
      "file": "arch/powerpc/kernel/eeh_pe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/eeh_pe.c:eeh_pe_state_clear",
        "arch/powerpc/kernel/eeh_pe.c:eeh_pe_mark_isolated",
        "arch/powerpc/kernel/eeh_pe.c:eeh_pe_state_mark",
        "arch/powerpc/kernel/eeh_pe.c:eeh_pe_traverse"
      ],
      "caller_func": [
        "arch/powerpc/kernel/eeh.c:eeh_pe_reset_full",
        "arch/powerpc/kernel/eeh_driver.c:eeh_handle_special_event",
        "arch/powerpc/kernel/eeh_driver.c:eeh_handle_normal_event",
        "arch/powerpc/kernel/eeh_driver.c:eeh_handle_normal_event",
        "arch/powerpc/kernel/eeh_driver.c:eeh_handle_normal_event",
        "arch/powerpc/kernel/eeh_driver.c:eeh_handle_normal_event",
        "arch/powerpc/kernel/eeh_driver.c:eeh_reset_device",
        "arch/powerpc/kernel/eeh_driver.c:eeh_clear_pe_frozen_state",
        "arch/powerpc/kernel/eeh_driver.c:eeh_pe_report",
        "arch/powerpc/kernel/eeh_driver.c:eeh_set_irq_state",
        "arch/powerpc/kernel/eeh_driver.c:eeh_set_channel_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282454912,
      "name": "eeh_pe_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct eeh_pe * eeh_pe_next(struct eeh_pe * pe, struct eeh_pe * root)
```
</details>
</li>
</ul>
