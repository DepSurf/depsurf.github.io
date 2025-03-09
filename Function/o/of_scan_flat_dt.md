# Function: <code>of_scan_flat_dt</code>

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
int of_scan_flat_dt(int (*)(long unsigned int, const char *, int, void *) it, void * data)
```

```json
{
  "name": "of_scan_flat_dt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511301256,
      "name": "of_scan_flat_dt",
      "external": true,
      "loc": "drivers/of/fdt.c:629",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/acpi.c:acpi_boot_table_init",
        "arch/arm64/mm/init.c:arm64_memblock_init",
        "arch/arm64/mm/init.c:arm64_memblock_init",
        "arch/arm/xen/enlighten.c:xen_early_init",
        "drivers/firmware/efi/efi.c:efi_get_fdt_params",
        "drivers/of/fdt.c:early_init_dt_scan_nodes",
        "drivers/of/fdt.c:early_init_dt_scan_nodes",
        "drivers/of/fdt.c:early_init_dt_scan_nodes",
        "drivers/of/fdt.c:early_init_fdt_scan_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511301256,
      "name": "of_scan_flat_dt",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int of_scan_flat_dt(int (*)(long unsigned int, const char *, int, void *) it, void * data)
```

```json
{
  "name": "of_scan_flat_dt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243961252,
      "name": "of_scan_flat_dt",
      "external": true,
      "loc": "drivers/of/fdt.c:629",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-exynos/exynos.c:exynos_init_io",
        "arch/arm/mach-mvebu/board-v7.c:mvebu_memblock_reserve",
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_reserve",
        "drivers/firmware/efi/efi.c:efi_get_fdt_params",
        "drivers/of/fdt.c:early_init_dt_scan_nodes",
        "drivers/of/fdt.c:early_init_dt_scan_nodes",
        "drivers/of/fdt.c:early_init_dt_scan_nodes",
        "drivers/of/fdt.c:early_init_fdt_scan_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243961252,
      "name": "of_scan_flat_dt",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int of_scan_flat_dt(int (*)(long unsigned int, const char *, int, void *) it, void * data)
```

```json
{
  "name": "of_scan_flat_dt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302849652,
      "name": "of_scan_flat_dt",
      "external": true,
      "loc": "drivers/of/fdt.c:629",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/prom.c:early_get_first_memblock_info",
        "arch/powerpc/kernel/prom.c:early_get_first_memblock_info",
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_scan",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_init",
        "arch/powerpc/kernel/epapr_paravirt.c:epapr_paravirt_early_init",
        "arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_devtree",
        "arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_devtree",
        "arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_devtree",
        "arch/powerpc/mm/book3s64/hash_utils.c:htab_initialize",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:radix__early_init_devtree",
        "arch/powerpc/platforms/pseries/firmware.c:pseries_probe_fw_features",
        "drivers/of/fdt.c:early_init_dt_scan_nodes",
        "drivers/of/fdt.c:early_init_dt_scan_nodes",
        "drivers/of/fdt.c:early_init_dt_scan_nodes",
        "drivers/of/fdt.c:early_init_fdt_scan_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302849652,
      "name": "of_scan_flat_dt",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int of_scan_flat_dt(int (*)(long unsigned int, const char *, int, void *) it, void * data)
```

```json
{
  "name": "of_scan_flat_dt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270838370,
      "name": "of_scan_flat_dt",
      "external": true,
      "loc": "drivers/of/fdt.c:629",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:early_init_dt_scan_nodes",
        "drivers/of/fdt.c:early_init_dt_scan_nodes",
        "drivers/of/fdt.c:early_init_dt_scan_nodes",
        "drivers/of/fdt.c:early_init_fdt_scan_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270838370,
      "name": "of_scan_flat_dt",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int of_scan_flat_dt(int (*)(long unsigned int, const char *, int, void *) it, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_scan_flat_dt(int (*)(long unsigned int, const char *, int, void *) it, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_scan_flat_dt(int (*)(long unsigned int, const char *, int, void *) it, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_scan_flat_dt(int (*)(long unsigned int, const char *, int, void *) it, void * data)
```
</details>
</li>
</ul>
