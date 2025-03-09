# Function: <code>blk_alloc_queue_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582734368,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:683",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-core.c:blk_init_queue_node",
        "block/blk-mq.c:blk_mq_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582734368,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 666
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
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583016592,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:692",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016592,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583121424,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:693",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121424,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583177376,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:813",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/scsi/scsi_lib.c:scsi_alloc_queue",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583177376,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583352256,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:887",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/scsi/scsi_lib.c:scsi_old_alloc_queue",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583352256,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 746
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id, spinlock_t * lock)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583561824,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:997",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_queue_node",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/scsi/scsi_lib.c:scsi_old_alloc_queue",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583561824,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583681696,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:474",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681696,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583870448,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:472",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583870448,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 682
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
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583973328,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:476",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583973328,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
    }
  ]
}
```
</details>
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
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495792648,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:476",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495792648,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229148296,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:476",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229148296,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289979808,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:476",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289979808,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 828
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
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274937662,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:476",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274937662,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583942064,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:476",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942064,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
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
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583879008,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:476",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/nvdimm/pmem.c:pmem_attach_disk",
        "drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879008,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
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
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583925824,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:476",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925824,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
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
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```

```json
{
  "name": "blk_alloc_queue_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584027216,
      "name": "blk_alloc_queue_node",
      "external": true,
      "loc": "block/blk-core.c:476",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-mq.c:blk_mq_init_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027216,
      "name": "blk_alloc_queue_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>spinlock_t * lock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>spinlock_t * lock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct request_queue * blk_alloc_queue_node(gfp_t gfp_mask, int node_id)
```
</details>
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
