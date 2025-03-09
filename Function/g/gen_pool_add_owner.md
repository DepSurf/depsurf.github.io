# Function: <code>gen_pool_add_owner</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181504,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:182",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181504,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315200,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:182",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315200,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584725056,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:182",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_add_partition",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584725056,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584837856,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:183",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_add_partition",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584837856,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584882512,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:184",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584882512,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:184",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_add_partition",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592326448,
      "name": "gen_pool_add_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071585308096,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:184",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_add_partition",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594130777,
      "name": "gen_pool_add_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071586164880,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:184",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_add_partition",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596117464,
      "name": "gen_pool_add_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587159056,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:182",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_add_partition",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596643618,
      "name": "gen_pool_add_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587422240,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:184",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init",
        "kernel/dma/pool.c:atomic_pool_expand",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_add_partition",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597553295,
      "name": "gen_pool_add_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587757024,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496203880,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:182",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/remap.c:dma_atomic_pool_init",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe",
        "drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe",
        "drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe",
        "drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_init",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496203880,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229525160,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:182",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/dma-mapping.c:atomic_pool_init",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_add_pool",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_create",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229525160,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290486144,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:182",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290486144,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275253240,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:182",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275253240,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584283936,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:182",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584283936,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584219136,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:182",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584219136,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584266848,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:182",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584266848,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```

```json
{
  "name": "gen_pool_add_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584371456,
      "name": "gen_pool_add_owner",
      "external": true,
      "loc": "lib/genalloc.c:182",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_init",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/usb/core/hcd.c:usb_hcd_setup_local_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584371456,
      "name": "gen_pool_add_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int gen_pool_add_owner(struct gen_pool * pool, long unsigned int virt, phys_addr_t phys, size_t size, int nid, void * owner)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
