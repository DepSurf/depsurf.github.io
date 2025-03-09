# Function: <code>blk_queue_make_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582769808,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:158",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/block/brd.c:brd_alloc",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582769808,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583048208,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:158",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/block/brd.c:brd_alloc",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048208,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583153776,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:162",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583153776,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583211120,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:162",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211120,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583387824,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:163",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583387824,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583597728,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:163",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583597728,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583703376,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:109",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703376,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583892016,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:110",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892016,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583995296,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:111",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583995296,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495822472,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:111",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495822472,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229172148,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:111",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229172148,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290011664,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:111",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290011664,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274957350,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:111",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274957350,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964032,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:111",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964032,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583900944,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:111",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/nvdimm/pmem.c:pmem_attach_disk",
        "drivers/nvdimm/blk.c:nd_blk_probe",
        "drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583900944,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583947792,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:111",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947792,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
```

```json
{
  "name": "blk_queue_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049776,
      "name": "blk_queue_make_request",
      "external": true,
      "loc": "block/blk-settings.c:111",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049776,
      "name": "blk_queue_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void blk_queue_make_request(struct request_queue * q, make_request_fn * mfn)
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
