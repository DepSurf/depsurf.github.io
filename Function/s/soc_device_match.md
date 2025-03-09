# Function: <code>soc_device_match</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "soc_device_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "soc_device_match",
      "external": false,
      "loc": "include/linux/sys_soc.h:44",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "soc_device_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "soc_device_match",
      "external": false,
      "loc": "include/linux/sys_soc.h:44",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "soc_device_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "soc_device_match",
      "external": false,
      "loc": "include/linux/sys_soc.h:44",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "soc_device_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "soc_device_match",
      "external": false,
      "loc": "include/linux/sys_soc.h:44",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "soc_device_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "soc_device_match",
      "external": false,
      "loc": "include/linux/sys_soc.h:44",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "soc_device_match",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "soc_device_match",
      "external": false,
      "loc": "include/linux/sys_soc.h:44",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
const struct soc_device_attribute * soc_device_match(const struct soc_device_attribute * matches)
```

```json
{
  "name": "soc_device_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590872304,
      "name": "soc_device_match",
      "external": true,
      "loc": "drivers/base/soc.c:258",
      "file": "drivers/base/soc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590872304,
      "name": "soc_device_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
const struct soc_device_attribute * soc_device_match(const struct soc_device_attribute * matches)
```

```json
{
  "name": "soc_device_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591215856,
      "name": "soc_device_match",
      "external": true,
      "loc": "drivers/base/soc.c:258",
      "file": "drivers/base/soc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591215856,
      "name": "soc_device_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
const struct soc_device_attribute * soc_device_match(const struct soc_device_attribute * matches)
```

```json
{
  "name": "soc_device_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499194648,
      "name": "soc_device_match",
      "external": true,
      "loc": "drivers/base/soc.c:241",
      "file": "drivers/base/soc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/sh-pfc/pfc-r8a7795.c:r8a7795_pinmux_init",
        "drivers/clk/renesas/r8a7795-cpg-mssr.c:r8a7795_cpg_mssr_init",
        "drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_init",
        "drivers/soc/renesas/r8a774c0-sysc.c:r8a774c0_sysc_init",
        "drivers/soc/renesas/r8a7795-sysc.c:r8a7795_sysc_init",
        "drivers/soc/renesas/r8a77990-sysc.c:r8a77990_sysc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499194648,
      "name": "soc_device_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
const struct soc_device_attribute * soc_device_match(const struct soc_device_attribute * matches)
```

```json
{
  "name": "soc_device_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231727152,
      "name": "soc_device_match",
      "external": true,
      "loc": "drivers/base/soc.c:241",
      "file": "drivers/base/soc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/renesas/rcar-gen2-cpg.c:rcar_gen2_cpg_init",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_of_xlate",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_of_xlate",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231727152,
      "name": "soc_device_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
const struct soc_device_attribute * soc_device_match(const struct soc_device_attribute * matches)
```

```json
{
  "name": "soc_device_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292402144,
      "name": "soc_device_match",
      "external": true,
      "loc": "drivers/base/soc.c:241",
      "file": "drivers/base/soc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292402144,
      "name": "soc_device_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
const struct soc_device_attribute * soc_device_match(const struct soc_device_attribute * matches)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
const struct soc_device_attribute * soc_device_match(const struct soc_device_attribute * matches)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
const struct soc_device_attribute * soc_device_match(const struct soc_device_attribute * matches)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
const struct soc_device_attribute * soc_device_match(const struct soc_device_attribute * matches)
```
</details>
</li>
</ul>
