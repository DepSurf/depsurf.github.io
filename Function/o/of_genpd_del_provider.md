# Function: <code>of_genpd_del_provider</code>

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
void of_genpd_del_provider(struct device_node * np)
```

```json
{
  "name": "of_genpd_del_provider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499094912,
      "name": "of_genpd_del_provider",
      "external": true,
      "loc": "drivers/base/power/domain.c:2165",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/imx/gpcv2.c:imx_pgc_domain_remove",
        "drivers/soc/xilinx/zynqmp_pm_domains.c:zynqmp_gpd_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499094912,
      "name": "of_genpd_del_provider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void of_genpd_del_provider(struct device_node * np)
```

```json
{
  "name": "of_genpd_del_provider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231647324,
      "name": "of_genpd_del_provider",
      "external": true,
      "loc": "drivers/base/power/domain.c:2165",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/imx/gpc.c:imx_pgc_power_domain_remove",
        "drivers/soc/imx/gpcv2.c:imx_pgc_domain_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231647324,
      "name": "of_genpd_del_provider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void of_genpd_del_provider(struct device_node * np)
```

```json
{
  "name": "of_genpd_del_provider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292278640,
      "name": "of_genpd_del_provider",
      "external": true,
      "loc": "drivers/base/power/domain.c:2165",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292278640,
      "name": "of_genpd_del_provider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void of_genpd_del_provider(struct device_node * np)
```

```json
{
  "name": "of_genpd_del_provider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276421888,
      "name": "of_genpd_del_provider",
      "external": true,
      "loc": "drivers/base/power/domain.c:2165",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276421888,
      "name": "of_genpd_del_provider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void of_genpd_del_provider(struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void of_genpd_del_provider(struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void of_genpd_del_provider(struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void of_genpd_del_provider(struct device_node * np)
```
</details>
</li>
</ul>
