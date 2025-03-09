# Function: <code>of_get_flat_dt_prop</code>

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
const void * of_get_flat_dt_prop(long unsigned int node, const char * name, int * size)
```

```json
{
  "name": "of_get_flat_dt_prop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511301784,
      "name": "of_get_flat_dt_prop",
      "external": true,
      "loc": "drivers/of/fdt.c:710",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/init.c:early_init_dt_scan_usablemem",
        "arch/arm64/mm/init.c:early_init_dt_scan_elfcorehdr",
        "arch/arm/xen/enlighten.c:fdt_find_hyper_node",
        "kernel/dma/contiguous.c:rmem_cma_setup",
        "kernel/dma/contiguous.c:rmem_cma_setup",
        "kernel/dma/contiguous.c:rmem_cma_setup",
        "kernel/dma/coherent.c:rmem_dma_setup",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/firmware/efi/efi.c:fdt_find_uefi_params",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_root",
        "drivers/of/fdt.c:early_init_dt_scan_root",
        "drivers/of/fdt.c:of_flat_dt_match_machine",
        "drivers/of/fdt.c:of_flat_dt_get_machine_name",
        "drivers/of/fdt.c:of_flat_dt_get_machine_name",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511301784,
      "name": "of_get_flat_dt_prop",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
const void * of_get_flat_dt_prop(long unsigned int node, const char * name, int * size)
```

```json
{
  "name": "of_get_flat_dt_prop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243961756,
      "name": "of_get_flat_dt_prop",
      "external": true,
      "loc": "drivers/of/fdt.c:710",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/devtree.c:setup_machine_fdt",
        "arch/arm/mach-exynos/exynos.c:exynos_fdt_map_chipid",
        "arch/arm/mach-mvebu/board-v7.c:mvebu_scan_mem",
        "arch/arm/mach-mvebu/board-v7.c:mvebu_scan_mem",
        "arch/arm/mach-mvebu/board-v7.c:mvebu_scan_mem",
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_scan_mem",
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_scan_mem",
        "arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_scan_mem",
        "kernel/dma/contiguous.c:rmem_cma_setup",
        "kernel/dma/contiguous.c:rmem_cma_setup",
        "kernel/dma/contiguous.c:rmem_cma_setup",
        "kernel/dma/coherent.c:rmem_dma_setup",
        "kernel/dma/coherent.c:rmem_dma_setup",
        "kernel/dma/coherent.c:rmem_dma_setup",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/firmware/efi/efi.c:fdt_find_uefi_params",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_root",
        "drivers/of/fdt.c:early_init_dt_scan_root",
        "drivers/of/fdt.c:of_flat_dt_match_machine",
        "drivers/of/fdt.c:of_flat_dt_get_machine_name",
        "drivers/of/fdt.c:of_flat_dt_get_machine_name",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243961756,
      "name": "of_get_flat_dt_prop",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 56
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
const void * of_get_flat_dt_prop(long unsigned int node, const char * name, int * size)
```

```json
{
  "name": "of_get_flat_dt_prop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302850348,
      "name": "of_get_flat_dt_prop",
      "external": true,
      "loc": "drivers/of/fdt.c:710",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/prom.c:early_init_dt_scan_chosen_ppc",
        "arch/powerpc/kernel/prom.c:early_init_dt_scan_chosen_ppc",
        "arch/powerpc/kernel/prom.c:early_init_dt_scan_chosen_ppc",
        "arch/powerpc/kernel/prom.c:early_init_dt_scan_chosen_ppc",
        "arch/powerpc/kernel/prom.c:early_init_dt_scan_chosen_ppc",
        "arch/powerpc/kernel/prom.c:early_init_dt_scan_chosen_ppc",
        "arch/powerpc/kernel/prom.c:early_init_dt_scan_chosen_ppc",
        "arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus",
        "arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus",
        "arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus",
        "arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus",
        "arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus",
        "arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus",
        "arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus",
        "arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus",
        "arch/powerpc/kernel/rtas.c:early_init_dt_scan_rtas",
        "arch/powerpc/kernel/rtas.c:early_init_dt_scan_rtas",
        "arch/powerpc/kernel/rtas.c:early_init_dt_scan_rtas",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_scan_callback",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_scan_callback",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:scan_cpufeatures_subnodes",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:cpufeatures_deps_enable",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_init",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:fdt_find_cpu_features",
        "arch/powerpc/kernel/epapr_paravirt.c:early_init_dt_scan_epapr",
        "arch/powerpc/mm/init_64.c:mmu_early_init_devtree",
        "arch/powerpc/mm/drmem.c:walk_drmem_lmbs_early",
        "arch/powerpc/mm/drmem.c:walk_drmem_lmbs_early",
        "arch/powerpc/mm/drmem.c:walk_drmem_lmbs_early",
        "arch/powerpc/mm/drmem.c:walk_drmem_lmbs_early",
        "arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_pftsize",
        "arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_pftsize",
        "arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_hugepage_blocks",
        "arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_hugepage_blocks",
        "arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_hugepage_blocks",
        "arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_page_sizes",
        "arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_page_sizes",
        "arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_seg_sizes",
        "arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_seg_sizes",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:radix_dt_scan_page_sizes",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:radix_dt_scan_page_sizes",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:radix_dt_scan_page_sizes",
        "arch/powerpc/sysdev/xive/spapr.c:xive_spapr_init",
        "arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_recoverable_ranges",
        "arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_opal",
        "arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_opal",
        "arch/powerpc/platforms/powernv/opal.c:early_init_dt_scan_opal",
        "arch/powerpc/platforms/powernv/opal-fadump.c:opal_fadump_dt_scan",
        "arch/powerpc/platforms/powernv/opal-fadump.c:opal_fadump_dt_scan",
        "arch/powerpc/platforms/pseries/firmware.c:probe_fw_features",
        "arch/powerpc/platforms/pseries/firmware.c:probe_fw_features",
        "arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_dt_scan",
        "arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_dt_scan",
        "arch/powerpc/platforms/pseries/rtas-fadump.c:rtas_fadump_dt_scan",
        "kernel/dma/coherent.c:rmem_dma_setup",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_root",
        "drivers/of/fdt.c:early_init_dt_scan_root",
        "drivers/of/fdt.c:of_flat_dt_match_machine",
        "drivers/of/fdt.c:of_flat_dt_get_machine_name",
        "drivers/of/fdt.c:of_flat_dt_get_machine_name",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302850348,
      "name": "of_get_flat_dt_prop",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
const void * of_get_flat_dt_prop(long unsigned int node, const char * name, int * size)
```

```json
{
  "name": "of_get_flat_dt_prop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270838812,
      "name": "of_get_flat_dt_prop",
      "external": true,
      "loc": "drivers/of/fdt.c:710",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/contiguous.c:rmem_cma_setup",
        "kernel/dma/contiguous.c:rmem_cma_setup",
        "kernel/dma/contiguous.c:rmem_cma_setup",
        "kernel/dma/coherent.c:rmem_dma_setup",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/tty/serial/earlycon.c:of_setup_earlycon",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_chosen",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_memory",
        "drivers/of/fdt.c:early_init_dt_scan_root",
        "drivers/of/fdt.c:early_init_dt_scan_root",
        "drivers/of/fdt.c:of_flat_dt_match_machine",
        "drivers/of/fdt.c:of_flat_dt_get_machine_name",
        "drivers/of/fdt.c:of_flat_dt_get_machine_name",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/fdt.c:__fdt_scan_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270838812,
      "name": "of_get_flat_dt_prop",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
const void * of_get_flat_dt_prop(long unsigned int node, const char * name, int * size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
const void * of_get_flat_dt_prop(long unsigned int node, const char * name, int * size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
const void * of_get_flat_dt_prop(long unsigned int node, const char * name, int * size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
const void * of_get_flat_dt_prop(long unsigned int node, const char * name, int * size)
```
</details>
</li>
</ul>
