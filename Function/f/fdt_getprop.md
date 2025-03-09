# Function: <code>fdt_getprop</code>

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
const void * fdt_getprop(const void * fdt, int nodeoffset, const char * name, int * lenp)
```

```json
{
  "name": "fdt_getprop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510861968,
      "name": "fdt_getprop",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:480",
      "file": "lib/fdt_ro.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/fdt_ro.c:fdt_node_check_compatible",
        "lib/fdt_ro.c:fdt_stringlist_get",
        "lib/fdt_ro.c:fdt_stringlist_search",
        "lib/fdt_ro.c:fdt_stringlist_count",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_get_phandle",
        "lib/fdt_ro.c:fdt_get_phandle"
      ],
      "caller_func": [
        "arch/arm64/kernel/kaslr.c:kaslr_early_init",
        "arch/arm64/kernel/kaslr.c:kaslr_early_init",
        "lib/fdt_wip.c:fdt_setprop_inplace",
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:of_fdt_is_compatible",
        "drivers/of/fdt.c:of_get_flat_dt_prop",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt_address.c:fdt_translate_address",
        "drivers/of/fdt_address.c:fdt_bus_default_count_cells",
        "drivers/of/fdt_address.c:fdt_bus_default_count_cells",
        "lib/fdt_ro.c:fdt_node_check_compatible",
        "lib/fdt_ro.c:fdt_stringlist_get",
        "lib/fdt_ro.c:fdt_stringlist_search",
        "lib/fdt_ro.c:fdt_stringlist_count",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_get_phandle",
        "lib/fdt_ro.c:fdt_get_phandle",
        "lib/fdt_wip.c:fdt_setprop_inplace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503812120,
      "name": "fdt_getprop",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
const void * fdt_getprop(const void * fdt, int nodeoffset, const char * name, int * lenp)
```

```json
{
  "name": "fdt_getprop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236433960,
      "name": "fdt_getprop",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:480",
      "file": "lib/fdt_ro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:of_fdt_is_compatible",
        "drivers/of/fdt.c:of_get_flat_dt_prop",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt_address.c:of_flat_dt_translate_address",
        "drivers/of/fdt_address.c:fdt_bus_default_count_cells",
        "drivers/of/fdt_address.c:fdt_bus_default_count_cells",
        "lib/fdt_ro.c:fdt_node_check_compatible",
        "lib/fdt_ro.c:fdt_stringlist_get",
        "lib/fdt_ro.c:fdt_stringlist_search",
        "lib/fdt_ro.c:fdt_stringlist_count",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_get_phandle",
        "lib/fdt_ro.c:fdt_get_phandle",
        "lib/fdt_wip.c:fdt_setprop_inplace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236433960,
      "name": "fdt_getprop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
const void * fdt_getprop(const void * fdt, int nodeoffset, const char * name, int * lenp)
```

```json
{
  "name": "fdt_getprop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297652512,
      "name": "fdt_getprop",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:480",
      "file": "lib/fdt_ro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/machine_kexec_file_64.c:setup_new_fdt",
        "arch/powerpc/kernel/machine_kexec_file_64.c:setup_new_fdt",
        "arch/powerpc/kernel/ima_kexec.c:remove_ima_buffer",
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:of_fdt_is_compatible",
        "drivers/of/fdt.c:of_get_flat_dt_prop",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt_address.c:fdt_translate_address",
        "drivers/of/fdt_address.c:fdt_translate_address",
        "drivers/of/fdt_address.c:fdt_bus_default_count_cells",
        "drivers/of/fdt_address.c:fdt_bus_default_count_cells",
        "lib/fdt_ro.c:fdt_node_check_compatible",
        "lib/fdt_ro.c:fdt_stringlist_get",
        "lib/fdt_ro.c:fdt_stringlist_search",
        "lib/fdt_ro.c:fdt_stringlist_count",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_get_phandle",
        "lib/fdt_ro.c:fdt_get_phandle",
        "lib/fdt_wip.c:fdt_setprop_inplace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297652512,
      "name": "fdt_getprop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
const void * fdt_getprop(const void * fdt, int nodeoffset, const char * name, int * lenp)
```

```json
{
  "name": "fdt_getprop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279710454,
      "name": "fdt_getprop",
      "external": true,
      "loc": "scripts/dtc/libfdt/fdt_ro.c:480",
      "file": "lib/fdt_ro.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/fdt_ro.c:fdt_node_check_compatible",
        "lib/fdt_ro.c:fdt_stringlist_get",
        "lib/fdt_ro.c:fdt_stringlist_search",
        "lib/fdt_ro.c:fdt_stringlist_count",
        "lib/fdt_ro.c:fdt_node_offset_by_prop_value",
        "lib/fdt_ro.c:fdt_get_phandle",
        "lib/fdt_ro.c:fdt_get_phandle"
      ],
      "caller_func": [
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:early_init_dt_scan_chosen_stdout",
        "drivers/of/fdt.c:of_fdt_is_compatible",
        "drivers/of/fdt.c:of_get_flat_dt_prop",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt.c:of_fdt_limit_memory",
        "drivers/of/fdt_address.c:fdt_translate_address",
        "drivers/of/fdt_address.c:fdt_translate_address",
        "drivers/of/fdt_address.c:fdt_bus_default_count_cells",
        "drivers/of/fdt_address.c:fdt_bus_default_count_cells",
        "lib/fdt_wip.c:fdt_setprop_inplace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279708118,
      "name": "fdt_getprop",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
const void * fdt_getprop(const void * fdt, int nodeoffset, const char * name, int * lenp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
const void * fdt_getprop(const void * fdt, int nodeoffset, const char * name, int * lenp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
const void * fdt_getprop(const void * fdt, int nodeoffset, const char * name, int * lenp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
const void * fdt_getprop(const void * fdt, int nodeoffset, const char * name, int * lenp)
```
</details>
</li>
</ul>
