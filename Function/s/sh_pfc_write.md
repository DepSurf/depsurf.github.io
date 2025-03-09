# Function: <code>sh_pfc_write</code>

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
void sh_pfc_write(struct sh_pfc * pfc, u32 reg, u32 data)
```

```json
{
  "name": "sh_pfc_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496643440,
      "name": "sh_pfc_write",
      "external": true,
      "loc": "drivers/pinctrl/sh-pfc/core.c:177",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_restore_reg",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set",
        "drivers/pinctrl/sh-pfc/pfc-r8a7796.c:r8a7796_pinmux_set_bias",
        "drivers/pinctrl/sh-pfc/pfc-r8a7796.c:r8a7796_pinmux_set_bias",
        "drivers/pinctrl/sh-pfc/pfc-r8a77990.c:r8a77990_pinmux_set_bias",
        "drivers/pinctrl/sh-pfc/pfc-r8a77990.c:r8a77990_pinmux_set_bias",
        "drivers/pinctrl/sh-pfc/pfc-r8a7795.c:r8a7795_pinmux_set_bias",
        "drivers/pinctrl/sh-pfc/pfc-r8a7795.c:r8a7795_pinmux_set_bias",
        "drivers/pinctrl/sh-pfc/pfc-r8a7795-es1.c:r8a7795es1_pinmux_set_bias",
        "drivers/pinctrl/sh-pfc/pfc-r8a7795-es1.c:r8a7795es1_pinmux_set_bias",
        "drivers/pinctrl/sh-pfc/pfc-r8a77965.c:r8a77965_pinmux_set_bias",
        "drivers/pinctrl/sh-pfc/pfc-r8a77965.c:r8a77965_pinmux_set_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496643440,
      "name": "sh_pfc_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void sh_pfc_write(struct sh_pfc * pfc, u32 reg, u32 data)
```

```json
{
  "name": "sh_pfc_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229955760,
      "name": "sh_pfc_write",
      "external": true,
      "loc": "drivers/pinctrl/sh-pfc/core.c:177",
      "file": "drivers/pinctrl/sh-pfc/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_restore_reg",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229955760,
      "name": "sh_pfc_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void sh_pfc_write(struct sh_pfc * pfc, u32 reg, u32 data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void sh_pfc_write(struct sh_pfc * pfc, u32 reg, u32 data)
```
</details>
</li>
</ul>
