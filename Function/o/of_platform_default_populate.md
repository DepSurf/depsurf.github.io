# Function: <code>of_platform_default_populate</code>

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
int of_platform_default_populate(struct device_node * root, const struct of_dev_auxdata * lookup, struct device * parent)
```

```json
{
  "name": "of_platform_default_populate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511300612,
      "name": "of_platform_default_populate",
      "external": true,
      "loc": "drivers/of/platform.c:497",
      "file": "drivers/of/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/of/platform.c:of_platform_default_populate_init"
      ],
      "caller_func": [
        "drivers/bus/imx-weim.c:weim_parse_dt",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501616424,
      "name": "of_platform_default_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int of_platform_default_populate(struct device_node * root, const struct of_dev_auxdata * lookup, struct device * parent)
```

```json
{
  "name": "of_platform_default_populate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243960612,
      "name": "of_platform_default_populate",
      "external": true,
      "loc": "drivers/of/platform.c:497",
      "file": "drivers/of/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/of/platform.c:of_platform_default_populate_init"
      ],
      "caller_func": [
        "arch/arm/mach-imx/mach-imx6q.c:imx6q_init_machine",
        "arch/arm/mach-imx/mach-imx6sl.c:imx6sl_init_machine",
        "arch/arm/mach-imx/mach-imx6sx.c:imx6sx_init_machine",
        "arch/arm/mach-imx/mach-imx6ul.c:imx6ul_init_machine",
        "arch/arm/mach-imx/mach-imx7ulp.c:imx7ulp_init_machine",
        "arch/arm/mach-tegra/tegra.c:tegra_dt_init",
        "drivers/bus/imx-weim.c:weim_parse_dt",
        "drivers/bus/qcom-ebi2.c:qcom_ebi2_probe",
        "drivers/bus/uniphier-system-bus.c:uniphier_system_bus_probe",
        "drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe",
        "drivers/memory/omap-gpmc.c:gpmc_probe_generic_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234139588,
      "name": "of_platform_default_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int of_platform_default_populate(struct device_node * root, const struct of_dev_auxdata * lookup, struct device * parent)
```

```json
{
  "name": "of_platform_default_populate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295043456,
      "name": "of_platform_default_populate",
      "external": true,
      "loc": "drivers/of/platform.c:497",
      "file": "drivers/of/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295043456,
      "name": "of_platform_default_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int of_platform_default_populate(struct device_node * root, const struct of_dev_auxdata * lookup, struct device * parent)
```

```json
{
  "name": "of_platform_default_populate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270837722,
      "name": "of_platform_default_populate",
      "external": true,
      "loc": "drivers/of/platform.c:497",
      "file": "drivers/of/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/of/platform.c:of_platform_default_populate_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278079712,
      "name": "of_platform_default_populate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int of_platform_default_populate(struct device_node * root, const struct of_dev_auxdata * lookup, struct device * parent)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_platform_default_populate(struct device_node * root, const struct of_dev_auxdata * lookup, struct device * parent)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_platform_default_populate(struct device_node * root, const struct of_dev_auxdata * lookup, struct device * parent)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_platform_default_populate(struct device_node * root, const struct of_dev_auxdata * lookup, struct device * parent)
```
</details>
</li>
</ul>
