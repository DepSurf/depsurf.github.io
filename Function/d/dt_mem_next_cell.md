# Function: <code>dt_mem_next_cell</code>

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
u64 dt_mem_next_cell(int s, const __be32 * * cellp)
```

```json
{
  "name": "dt_mem_next_cell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511303700,
      "name": "dt_mem_next_cell",
      "external": true,
      "loc": "drivers/of/fdt.c:985",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/init.c:early_init_dt_scan_usablemem",
        "arch/arm64/mm/init.c:early_init_dt_scan_usablemem",
        "arch/arm64/mm/init.c:early_init_dt_scan_elfcorehdr",
        "arch/arm64/mm/init.c:early_init_dt_scan_elfcorehdr",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511303700,
      "name": "dt_mem_next_cell",
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
u64 dt_mem_next_cell(int s, const __be32 * * cellp)
```

```json
{
  "name": "dt_mem_next_cell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243963764,
      "name": "dt_mem_next_cell",
      "external": true,
      "loc": "drivers/of/fdt.c:985",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-mvebu/board-v7.c:mvebu_scan_mem",
        "arch/arm/mach-mvebu/board-v7.c:mvebu_scan_mem",
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_scan_mem",
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_scan_mem",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243963764,
      "name": "dt_mem_next_cell",
      "section": ".init.text",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
u64 dt_mem_next_cell(int s, const __be32 * * cellp)
```

```json
{
  "name": "dt_mem_next_cell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302852720,
      "name": "dt_mem_next_cell",
      "external": true,
      "loc": "drivers/of/fdt.c:985",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/prom.c:early_init_drmem_lmb",
        "arch/powerpc/kernel/prom.c:early_init_drmem_lmb",
        "arch/powerpc/kernel/prom.c:early_init_drmem_lmb",
        "arch/powerpc/mm/drmem.c:init_drmem_lmb_size",
        "arch/powerpc/mm/drmem.c:read_drconf_v2_cell",
        "arch/powerpc/mm/drmem.c:read_drconf_v1_cell",
        "arch/powerpc/mm/drmem.c:walk_drmem_lmbs_early",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302852720,
      "name": "dt_mem_next_cell",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 76
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
u64 dt_mem_next_cell(int s, const __be32 * * cellp)
```

```json
{
  "name": "dt_mem_next_cell",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270840614,
      "name": "dt_mem_next_cell",
      "external": true,
      "loc": "drivers/of/fdt.c:985",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270840614,
      "name": "dt_mem_next_cell",
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
u64 dt_mem_next_cell(int s, const __be32 * * cellp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
u64 dt_mem_next_cell(int s, const __be32 * * cellp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
u64 dt_mem_next_cell(int s, const __be32 * * cellp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
u64 dt_mem_next_cell(int s, const __be32 * * cellp)
```
</details>
</li>
</ul>
