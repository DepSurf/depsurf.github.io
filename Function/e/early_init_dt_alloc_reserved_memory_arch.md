# Function: <code>early_init_dt_alloc_reserved_memory_arch</code>

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
int early_init_dt_alloc_reserved_memory_arch(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, bool nomap, phys_addr_t * res_base)
```

```json
{
  "name": "early_init_dt_alloc_reserved_memory_arch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511308660,
      "name": "early_init_dt_alloc_reserved_memory_arch",
      "external": false,
      "loc": "drivers/of/of_reserved_mem.c:29",
      "file": "drivers/of/of_reserved_mem.c",
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
      "addr": 18446603336511308660,
      "name": "early_init_dt_alloc_reserved_memory_arch",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 144
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
int early_init_dt_alloc_reserved_memory_arch(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, bool nomap, phys_addr_t * res_base)
```

```json
{
  "name": "early_init_dt_alloc_reserved_memory_arch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243969164,
      "name": "early_init_dt_alloc_reserved_memory_arch",
      "external": false,
      "loc": "drivers/of/of_reserved_mem.c:29",
      "file": "drivers/of/of_reserved_mem.c",
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
      "addr": 3243969164,
      "name": "early_init_dt_alloc_reserved_memory_arch",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 112
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
int early_init_dt_alloc_reserved_memory_arch(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, bool nomap, phys_addr_t * res_base)
```

```json
{
  "name": "early_init_dt_alloc_reserved_memory_arch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302858664,
      "name": "early_init_dt_alloc_reserved_memory_arch",
      "external": false,
      "loc": "drivers/of/of_reserved_mem.c:29",
      "file": "drivers/of/of_reserved_mem.c",
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
      "addr": 13835058055302858664,
      "name": "early_init_dt_alloc_reserved_memory_arch",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 188
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
int early_init_dt_alloc_reserved_memory_arch(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, bool nomap, phys_addr_t * res_base)
```

```json
{
  "name": "early_init_dt_alloc_reserved_memory_arch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270845172,
      "name": "early_init_dt_alloc_reserved_memory_arch",
      "external": false,
      "loc": "drivers/of/of_reserved_mem.c:29",
      "file": "drivers/of/of_reserved_mem.c",
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
      "addr": 18446743936270845172,
      "name": "early_init_dt_alloc_reserved_memory_arch",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 130
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
int early_init_dt_alloc_reserved_memory_arch(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, bool nomap, phys_addr_t * res_base)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int early_init_dt_alloc_reserved_memory_arch(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, bool nomap, phys_addr_t * res_base)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int early_init_dt_alloc_reserved_memory_arch(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, bool nomap, phys_addr_t * res_base)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int early_init_dt_alloc_reserved_memory_arch(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end, bool nomap, phys_addr_t * res_base)
```
</details>
</li>
</ul>
