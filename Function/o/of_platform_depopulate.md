# Function: <code>of_platform_depopulate</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void of_platform_depopulate(struct device * parent)
```

```json
{
  "name": "of_platform_depopulate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501613912,
      "name": "of_platform_depopulate",
      "external": true,
      "loc": "drivers/of/platform.c:576",
      "file": "drivers/of/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/hisi_lpc.c:hisi_lpc_remove",
        "drivers/firmware/ti_sci.c:ti_sci_remove",
        "drivers/of/platform.c:devm_of_platform_populate_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501613912,
      "name": "of_platform_depopulate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void of_platform_depopulate(struct device * parent)
```

```json
{
  "name": "of_platform_depopulate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234136500,
      "name": "of_platform_depopulate",
      "external": true,
      "loc": "drivers/of/platform.c:576",
      "file": "drivers/of/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/ti-sysc.c:sysc_remove",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_remove_dt",
        "drivers/of/platform.c:devm_of_platform_populate_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234136500,
      "name": "of_platform_depopulate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void of_platform_depopulate(struct device * parent)
```

```json
{
  "name": "of_platform_depopulate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295039584,
      "name": "of_platform_depopulate",
      "external": true,
      "loc": "drivers/of/platform.c:576",
      "file": "drivers/of/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/platform.c:devm_of_platform_populate_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295039584,
      "name": "of_platform_depopulate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void of_platform_depopulate(struct device * parent)
```

```json
{
  "name": "of_platform_depopulate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278077244,
      "name": "of_platform_depopulate",
      "external": true,
      "loc": "drivers/of/platform.c:576",
      "file": "drivers/of/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/platform.c:devm_of_platform_populate_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278077244,
      "name": "of_platform_depopulate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
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
void of_platform_depopulate(struct device * parent)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void of_platform_depopulate(struct device * parent)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void of_platform_depopulate(struct device * parent)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void of_platform_depopulate(struct device * parent)
```
</details>
</li>
</ul>
