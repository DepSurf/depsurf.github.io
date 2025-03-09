# Function: <code>__xa_insert</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589432720,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1458",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589432720,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589890720,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1472",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589890720,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590116672,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1483",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590116672,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585121088,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1485",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585121088,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585271648,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1635",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271648,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585155392,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1636",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "fs/io_uring.c:io_provide_buffers",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585155392,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585608240,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1636",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "fs/io_uring.c:io_provide_buffers",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585608240,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586764864,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1643",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "kernel/irq/msi.c:msi_add_simple_msi_descs",
        "kernel/irq/msi.c:msi_add_msi_desc",
        "block/blk-mq.c:blk_mq_init_hctx",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition",
        "drivers/dax/super.c:dax_add_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764864,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595929296,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1643",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "kernel/irq/msi.c:msi_insert_desc",
        "block/blk-mq.c:blk_mq_init_hctx",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition",
        "drivers/pci/doe.c:pcim_doe_create_mb",
        "drivers/dax/super.c:dax_add_host",
        "net/core/devlink.c:devl_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595929296,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596447696,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1641",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "kernel/irq/msi.c:msi_insert_desc",
        "block/blk-mq.c:blk_mq_init_hctx",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition",
        "drivers/pci/doe.c:pci_doe_init",
        "drivers/pci/doe.c:pci_doe_create_mb",
        "drivers/dax/super.c:dax_add_host",
        "net/devlink/leftover.c:devl_params_register",
        "net/devlink/leftover.c:devl_port_register_with_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596447696,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597343056,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1641",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "kernel/irq/msi.c:msi_insert_desc",
        "block/blk-mq.c:blk_mq_init_hctx",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:add_partition",
        "drivers/pci/doe.c:pci_doe_init",
        "drivers/pci/doe.c:pci_doe_create_mb",
        "drivers/dax/super.c:dax_add_host",
        "drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_add",
        "drivers/dpll/dpll_core.c:dpll_xa_ref_pin_add",
        "net/core/dev.c:__dev_change_net_namespace",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/devlink/dev.c:devl_nested_devlink_set",
        "net/devlink/port.c:devl_port_register_with_ops",
        "net/devlink/param.c:devl_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597343056,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503899848,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1483",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503899848,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236527552,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1483",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236527552,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297767952,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1483",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297767952,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279787842,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1483",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279787842,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589718928,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1483",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589718928,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589444704,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1483",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589444704,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590162304,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1483",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590162304,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590213088,
      "name": "__xa_insert",
      "external": true,
      "loc": "lib/xarray.c:1483",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590213088,
      "name": "__xa_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __xa_insert(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```
</details>
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
