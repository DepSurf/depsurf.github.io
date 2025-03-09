# Function: <code>list_sort</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583017488,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:104",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_flush_plug_list",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/misc/sram.c:sram_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583017488,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 601
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583308496,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:104",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_flush_plug_list",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/misc/sram.c:sram_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583308496,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583427808,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:104",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_flush_plug_list",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/misc/sram.c:sram_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427808,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 626
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583449136,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:101",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "block/blk-core.c:blk_flush_plug_list",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/misc/sram.c:sram_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583449136,
      "name": "list_sort.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 599
    },
    {
      "addr": 18446744071583449744,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583629232,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:102",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "block/blk-core.c:blk_flush_plug_list",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/misc/sram.c:sram_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629232,
      "name": "list_sort.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
    },
    {
      "addr": 18446744071583629840,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583846352,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:102",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "block/blk-core.c:blk_flush_plug_list",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/misc/sram.c:sram_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583845792,
      "name": "list_sort.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
    },
    {
      "addr": 18446744071583846372,
      "name": "list_sort.part.0.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583846352,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583930048,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:102",
      "file": "lib/list_sort.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "drivers/misc/sram.c:sram_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929488,
      "name": "list_sort.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
    },
    {
      "addr": 18446744071583930068,
      "name": "list_sort.part.0.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583930048,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584109008,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:188",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/misc/sram.c:sram_reserve_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584109008,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584231856,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:188",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/misc/sram.c:sram_reserve_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584231856,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584638720,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:188",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_sort_ioends",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/misc/sram.c:sram_reserve_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584638720,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584758256,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:188",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_sort_ioends",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/misc/sram.c:sram_reserve_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584758256,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
void list_sort(void * priv, struct list_head * head, list_cmp_func_t cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584786704,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:185",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_sort_ioends",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/misc/sram.c:sram_reserve_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786704,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void list_sort(void * priv, struct list_head * head, list_cmp_func_t cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585217472,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:185",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_sort_ioends",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/misc/sram.c:sram_reserve_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585217472,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void list_sort(void * priv, struct list_head * head, list_cmp_func_t cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586055456,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:185",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_sort_ioends",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows",
        "drivers/misc/sram.c:sram_reserve_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586055456,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void list_sort(void * priv, struct list_head * head, list_cmp_func_t cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587039312,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:185",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_sort_ioends",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows",
        "drivers/misc/sram.c:sram_reserve_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587039312,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void list_sort(void * priv, struct list_head * head, list_cmp_func_t cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587296416,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:185",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_sort_ioends",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "drivers/acpi/numa/hmat.c:hmat_register_target_initiators",
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows",
        "drivers/misc/sram.c:sram_reserve_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587296416,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void list_sort(void * priv, struct list_head * head, list_cmp_func_t cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587582240,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:185",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_sort_ioends",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "drivers/acpi/numa/hmat.c:hmat_update_target_attrs",
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/gpu/drm/drm_modes.c:drm_mode_sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587582240,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496107256,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:188",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0",
        "virt/kvm/arm/vgic/vgic-its.c:vgic_its_save_tables_v0",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_reserve_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496107256,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 764
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
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229432496,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:188",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_reserve_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229432496,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290355056,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:188",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_reserve_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290355056,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1068
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
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275173050,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:188",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/misc/sram.c:sram_reserve_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275173050,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584200592,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:188",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/nvme/host/core.c:nvme_scan_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584200592,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584135808,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:188",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/acpi/nfit/core.c:acpi_nfit_init",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/misc/sram.c:sram_reserve_regions",
        "drivers/nvme/host/core.c:nvme_scan_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584135808,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584184352,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:188",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/misc/sram.c:sram_reserve_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584184352,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
void list_sort(void * priv, struct list_head * head, int (*)(void *, struct list_head *, struct list_head *) cmp)
```

```json
{
  "name": "list_sort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584288704,
      "name": "list_sort",
      "external": true,
      "loc": "lib/list_sort.c:188",
      "file": "lib/list_sort.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "drivers/acpi/hmat/hmat.c:hmat_register_target_initiators",
        "drivers/misc/sram.c:sram_reserve_regions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584288704,
      "name": "list_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*)(void *, struct list_head *, struct list_head *) cmp</code> ➡️ <code>list_cmp_func_t cmp</code>
</li>
</ul>
</details>
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
