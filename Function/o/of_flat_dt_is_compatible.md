# Function: <code>of_flat_dt_is_compatible</code>

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
int of_flat_dt_is_compatible(long unsigned int node, const char * compat)
```

```json
{
  "name": "of_flat_dt_is_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511302720,
      "name": "of_flat_dt_is_compatible",
      "external": true,
      "loc": "drivers/of/fdt.c:753",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/acpi.c:dt_scan_depth1_nodes",
        "arch/arm/xen/enlighten.c:fdt_find_hyper_node",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511302720,
      "name": "of_flat_dt_is_compatible",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int of_flat_dt_is_compatible(long unsigned int node, const char * compat)
```

```json
{
  "name": "of_flat_dt_is_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243962792,
      "name": "of_flat_dt_is_compatible",
      "external": true,
      "loc": "drivers/of/fdt.c:753",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-exynos/exynos.c:exynos_fdt_map_chipid",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243962792,
      "name": "of_flat_dt_is_compatible",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int of_flat_dt_is_compatible(long unsigned int node, const char * compat)
```

```json
{
  "name": "of_flat_dt_is_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302851500,
      "name": "of_flat_dt_is_compatible",
      "external": true,
      "loc": "drivers/of/fdt.c:753",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_scan_callback",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:fdt_find_cpu_features",
        "arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_opal",
        "arch/powerpc/platforms/powernv/ultravisor.c:early_init_dt_scan_ultravisor",
        "arch/powerpc/platforms/powernv/opal-fadump.c:opal_fadump_dt_scan",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302851500,
      "name": "of_flat_dt_is_compatible",
      "section": ".init.text",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int of_flat_dt_is_compatible(long unsigned int node, const char * compat)
```

```json
{
  "name": "of_flat_dt_is_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270839794,
      "name": "of_flat_dt_is_compatible",
      "external": true,
      "loc": "drivers/of/fdt.c:753",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270839794,
      "name": "of_flat_dt_is_compatible",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int of_flat_dt_is_compatible(long unsigned int node, const char * compat)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_flat_dt_is_compatible(long unsigned int node, const char * compat)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_flat_dt_is_compatible(long unsigned int node, const char * compat)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_flat_dt_is_compatible(long unsigned int node, const char * compat)
```
</details>
</li>
</ul>
