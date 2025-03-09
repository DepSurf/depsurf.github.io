# Function: <code>xa_store</code>

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
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589434448,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1388",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589434448,
      "name": "xa_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589892448,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1406",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589892448,
      "name": "xa_store",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590118400,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1417",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590118400,
      "name": "xa_store",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585120688,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1419",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:init_memory_block",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:__devlink_snapshot_id_decrement",
        "net/core/devlink.c:__devlink_snapshot_id_increment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585120688,
      "name": "xa_store",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585271248,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1569",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_uring_add_task_file",
        "drivers/base/memory.c:init_memory_block",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:__devlink_snapshot_id_decrement",
        "net/core/devlink.c:__devlink_snapshot_id_increment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271248,
      "name": "xa_store",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585154992,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1570",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "fs/io_uring.c:__io_uring_add_task_file",
        "block/bio.c:bioset_init",
        "drivers/base/memory.c:init_memory_block",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:__devlink_region_snapshot_create",
        "net/core/devlink.c:__devlink_snapshot_id_decrement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585154992,
      "name": "xa_store",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585607840,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1570",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "fs/io_uring.c:__io_uring_add_tctx_node",
        "block/bio.c:bioset_init",
        "drivers/base/memory.c:init_memory_block",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:__devlink_region_snapshot_create",
        "net/core/devlink.c:__devlink_snapshot_id_decrement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585607840,
      "name": "xa_store",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586764448,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1577",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "block/bio.c:bioset_init",
        "io_uring/io_uring.c:io_register_pbuf_ring",
        "io_uring/io_uring.c:__io_uring_add_tctx_node",
        "io_uring/io_uring.c:io_provide_buffers",
        "drivers/base/memory.c:add_memory_block",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:__devlink_region_snapshot_create",
        "net/core/devlink.c:__devlink_snapshot_id_decrement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764448,
      "name": "xa_store",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595928848,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1577",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "block/bio.c:bioset_init",
        "io_uring/tctx.c:__io_uring_add_tctx_node",
        "io_uring/kbuf.c:io_register_pbuf_ring",
        "io_uring/kbuf.c:io_provide_buffers",
        "drivers/pci/p2pdma.c:calc_map_type_and_dist",
        "drivers/base/memory.c:add_memory_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595928848,
      "name": "xa_store",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596447248,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1575",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "block/bio.c:bioset_init",
        "io_uring/tctx.c:__io_uring_add_tctx_node",
        "io_uring/kbuf.c:io_register_pbuf_ring",
        "io_uring/kbuf.c:io_provide_buffers",
        "drivers/pci/p2pdma.c:calc_map_type_and_dist",
        "drivers/base/memory.c:add_memory_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596447248,
      "name": "xa_store",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597342608,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1575",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "fs/libfs.c:simple_offset_rename_exchange",
        "fs/libfs.c:simple_offset_rename_exchange",
        "block/bio.c:bioset_init",
        "io_uring/tctx.c:__io_uring_add_tctx_node",
        "io_uring/kbuf.c:io_register_pbuf_ring",
        "io_uring/kbuf.c:io_provide_buffers",
        "drivers/pci/p2pdma.c:calc_map_type_and_dist",
        "drivers/base/memory.c:add_memory_block",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597342608,
      "name": "xa_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503899376,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1417",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503899376,
      "name": "xa_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236527084,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1417",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236527084,
      "name": "xa_store",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297767312,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1417",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297767312,
      "name": "xa_store",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279787490,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1417",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279787490,
      "name": "xa_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589720656,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1417",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589720656,
      "name": "xa_store",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589446432,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1417",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589446432,
      "name": "xa_store",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590164032,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1417",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590164032,
      "name": "xa_store",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590212688,
      "name": "xa_store",
      "external": true,
      "loc": "lib/xarray.c:1417",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590212688,
      "name": "xa_store",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void * xa_store(struct xarray * xa, long unsigned int index, void * entry, gfp_t gfp)
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
