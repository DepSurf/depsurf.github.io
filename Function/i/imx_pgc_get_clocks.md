# Function: <code>imx_pgc_get_clocks</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "imx_pgc_get_clocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "imx_pgc_get_clocks",
      "external": false,
      "loc": "drivers/soc/imx/gpcv2.c:445",
      "file": "drivers/soc/imx/gpcv2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe"
      ],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
int imx_pgc_get_clocks(struct device * dev, struct imx_pm_domain * domain)
```

```json
{
  "name": "imx_pgc_get_clocks",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230876872,
      "name": "imx_pgc_get_clocks",
      "external": false,
      "loc": "drivers/soc/imx/gpc.c:129",
      "file": "drivers/soc/imx/gpc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/imx/gpc.c:imx_gpc_probe",
        "drivers/soc/imx/gpc.c:imx_pgc_power_domain_probe"
      ]
    },
    {
      "addr": 0,
      "name": "imx_pgc_get_clocks",
      "external": false,
      "loc": "drivers/soc/imx/gpcv2.c:445",
      "file": "drivers/soc/imx/gpcv2.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/soc/imx/gpcv2.c:imx_pgc_domain_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230876872,
      "name": "imx_pgc_get_clocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int imx_pgc_get_clocks(struct device * dev, struct imx_pm_domain * domain)
```
</details>
</li>
</ul>
