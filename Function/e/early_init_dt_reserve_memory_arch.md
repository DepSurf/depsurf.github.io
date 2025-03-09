# Function: <code>early_init_dt_reserve_memory_arch</code>

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
int early_init_dt_reserve_memory_arch(phys_addr_t base, phys_addr_t size, bool nomap)
```

```json
{
  "name": "early_init_dt_reserve_memory_arch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511304376,
      "name": "early_init_dt_reserve_memory_arch",
      "external": true,
      "loc": "drivers/of/fdt.c:1153",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_fdt_reserve_self",
        "drivers/of/fdt.c:early_init_fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511304376,
      "name": "early_init_dt_reserve_memory_arch",
      "section": ".init.text",
      "bind": "STB_WEAK",
      "size": 76
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
int early_init_dt_reserve_memory_arch(phys_addr_t base, phys_addr_t size, bool nomap)
```

```json
{
  "name": "early_init_dt_reserve_memory_arch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243964908,
      "name": "early_init_dt_reserve_memory_arch",
      "external": true,
      "loc": "drivers/of/fdt.c:1153",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_fdt_reserve_self",
        "drivers/of/fdt.c:early_init_fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243964908,
      "name": "early_init_dt_reserve_memory_arch",
      "section": ".init.text",
      "bind": "STB_WEAK",
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
int early_init_dt_reserve_memory_arch(phys_addr_t base, phys_addr_t size, bool nomap)
```

```json
{
  "name": "early_init_dt_reserve_memory_arch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302853544,
      "name": "early_init_dt_reserve_memory_arch",
      "external": true,
      "loc": "drivers/of/fdt.c:1153",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_fdt_reserve_self",
        "drivers/of/fdt.c:early_init_fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302853544,
      "name": "early_init_dt_reserve_memory_arch",
      "section": ".init.text",
      "bind": "STB_WEAK",
      "size": 72
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
int early_init_dt_reserve_memory_arch(phys_addr_t base, phys_addr_t size, bool nomap)
```

```json
{
  "name": "early_init_dt_reserve_memory_arch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270841342,
      "name": "early_init_dt_reserve_memory_arch",
      "external": true,
      "loc": "drivers/of/fdt.c:1153",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_fdt_reserve_self",
        "drivers/of/fdt.c:early_init_fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270841342,
      "name": "early_init_dt_reserve_memory_arch",
      "section": ".init.text",
      "bind": "STB_WEAK",
      "size": 70
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
int early_init_dt_reserve_memory_arch(phys_addr_t base, phys_addr_t size, bool nomap)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int early_init_dt_reserve_memory_arch(phys_addr_t base, phys_addr_t size, bool nomap)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int early_init_dt_reserve_memory_arch(phys_addr_t base, phys_addr_t size, bool nomap)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int early_init_dt_reserve_memory_arch(phys_addr_t base, phys_addr_t size, bool nomap)
```
</details>
</li>
</ul>
