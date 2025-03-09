# Function: <code>gen_pool_alloc_algo_owner</code>

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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584180560,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:275",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "lib/genalloc.c:gen_pool_dma_alloc_algo",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584180560,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584314256,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:275",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "lib/genalloc.c:gen_pool_dma_alloc_algo",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584314256,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584726272,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:275",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "kernel/dma/pool.c:__dma_alloc_from_pool",
        "lib/genalloc.c:gen_pool_dma_alloc_algo",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584726272,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584839488,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:276",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "kernel/dma/pool.c:__dma_alloc_from_pool",
        "lib/genalloc.c:gen_pool_dma_alloc_algo",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584839488,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 518
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584884144,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:277",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "kernel/dma/pool.c:dma_alloc_from_pool",
        "lib/genalloc.c:gen_pool_dma_alloc_algo",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584884144,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:277",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "kernel/dma/pool.c:dma_alloc_from_pool",
        "lib/genalloc.c:gen_pool_dma_alloc_algo",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592326739,
      "name": "gen_pool_alloc_algo_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071585309920,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 559
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:277",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "kernel/dma/pool.c:dma_alloc_from_pool",
        "lib/genalloc.c:gen_pool_dma_alloc_algo",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594131068,
      "name": "gen_pool_alloc_algo_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071586167024,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:277",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "kernel/dma/pool.c:dma_alloc_from_pool",
        "lib/genalloc.c:gen_pool_dma_alloc_algo",
        "drivers/pci/p2pdma.c:pci_alloc_p2pmem",
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596117755,
      "name": "gen_pool_alloc_algo_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071587161472,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:275",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "kernel/dma/pool.c:__dma_alloc_from_pool",
        "lib/genalloc.c:gen_pool_dma_alloc_algo",
        "drivers/pci/p2pdma.c:pci_alloc_p2pmem",
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596643896,
      "name": "gen_pool_alloc_algo_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071587424608,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:277",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "kernel/dma/pool.c:__dma_alloc_from_pool",
        "lib/genalloc.c:gen_pool_dma_alloc_algo",
        "drivers/pci/p2pdma.c:pci_alloc_p2pmem",
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event",
        "drivers/acpi/apei/ghes.c:ghes_handle_aer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597553573,
      "name": "gen_pool_alloc_algo_owner.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071587759392,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496202832,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:275",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/remap.c:dma_alloc_from_pool",
        "lib/genalloc.c:gen_pool_dma_alloc_algo",
        "drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/soc/fsl/qbman/bman.c:bman_new_pool",
        "drivers/soc/fsl/qbman/qman.c:qman_alloc_range",
        "drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_alloc",
        "drivers/edac/altera_edac.c:ocram_alloc_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496202832,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229527308,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:275",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-imx/pm-imx6.c:imx6q_suspend_init",
        "arch/arm/mach-omap2/omap4-common.c:__omap4_sram_init",
        "lib/genalloc.c:gen_pool_dma_alloc_algo",
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229527308,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290484672,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:275",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:gen_pool_dma_alloc_algo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290484672,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275253454,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:275",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/genalloc.c:gen_pool_dma_alloc_algo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275253454,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584282992,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:275",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "lib/genalloc.c:gen_pool_dma_alloc_algo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584282992,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584218192,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:275",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "lib/genalloc.c:gen_pool_dma_alloc_algo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584218192,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584265904,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:275",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "lib/genalloc.c:gen_pool_dma_alloc_algo",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584265904,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
```

```json
{
  "name": "gen_pool_alloc_algo_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584371760,
      "name": "gen_pool_alloc_algo_owner",
      "external": true,
      "loc": "lib/genalloc.c:275",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_add",
        "lib/genalloc.c:gen_pool_dma_alloc_algo",
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584371760,
      "name": "gen_pool_alloc_algo_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
long unsigned int gen_pool_alloc_algo_owner(struct gen_pool * pool, size_t size, genpool_algo_t algo, void * data, void * * owner)
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
