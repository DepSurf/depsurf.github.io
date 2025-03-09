# Function: <code>xa_destroy</code>

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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589429120,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:1935",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589429120,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589886768,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:1962",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589886768,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590112720,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:1983",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590112720,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585117872,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:1986",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585117872,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585268256,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:2199",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "net/core/devlink.c:devlink_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585268256,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585151072,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:2200",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "net/core/devlink.c:devlink_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151072,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585603472,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:2200",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "net/core/devlink.c:devlink_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585603472,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586760512,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:2207",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "kernel/irq/msi.c:msi_device_data_release",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_release",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_ring_ctx_alloc",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "net/core/devlink.c:devlink_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586760512,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595924976,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:2207",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "kernel/irq/msi.c:msi_device_data_release",
        "kernel/irq/msi.c:msi_device_data_release",
        "block/blk-mq.c:blk_mq_release",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_ring_ctx_alloc",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/pci/doe.c:pci_doe_xa_destroy",
        "net/core/devlink.c:devlink_free",
        "net/core/devlink.c:devlink_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595924976,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596443280,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:2205",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "kernel/irq/msi.c:msi_device_data_release",
        "kernel/irq/msi.c:msi_device_data_release",
        "block/blk-mq.c:blk_mq_release",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_ring_ctx_alloc",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/pci/doe.c:pci_doe_destroy",
        "drivers/pci/doe.c:pci_doe_destroy",
        "drivers/pci/doe.c:pci_doe_init",
        "drivers/pci/doe.c:pci_doe_create_mb",
        "net/devlink/core.c:devlink_free",
        "net/devlink/core.c:devlink_free",
        "net/devlink/core.c:devlink_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596443280,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597338640,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:2211",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "kernel/irq/msi.c:msi_device_data_release",
        "kernel/irq/msi.c:msi_device_data_release",
        "fs/libfs.c:simple_offset_destroy",
        "block/blk-mq.c:blk_mq_release",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:disk_release",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "io_uring/io_uring.c:io_ring_ctx_alloc",
        "drivers/pci/p2pdma.c:pci_p2pdma_add_resource",
        "drivers/pci/doe.c:pci_doe_destroy",
        "drivers/pci/doe.c:pci_doe_destroy",
        "drivers/pci/doe.c:pci_doe_init",
        "drivers/pci/doe.c:pci_doe_create_mb",
        "drivers/dpll/dpll_core.c:dpll_pin_put",
        "drivers/dpll/dpll_core.c:dpll_pin_put",
        "drivers/dpll/dpll_core.c:dpll_pin_get",
        "drivers/dpll/dpll_core.c:dpll_pin_get",
        "drivers/dpll/dpll_core.c:dpll_device_put",
        "net/core/dev.c:netdev_exit",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/devlink/core.c:devlink_free",
        "net/devlink/core.c:devlink_free",
        "net/devlink/core.c:devlink_free",
        "net/devlink/core.c:devlink_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597338640,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503897128,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:1983",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503897128,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236523360,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:1983",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236523360,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297761984,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:1983",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297761984,
      "name": "xa_destroy",
      "section": ".text",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279784388,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:1983",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279784388,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589714976,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:1983",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589714976,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589440752,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:1983",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589440752,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590158352,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:1983",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590158352,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void xa_destroy(struct xarray * xa)
```

```json
{
  "name": "xa_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590208928,
      "name": "xa_destroy",
      "external": true,
      "loc": "lib/xarray.c:1983",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590208928,
      "name": "xa_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void xa_destroy(struct xarray * xa)
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
