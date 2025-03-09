# Function: <code>generic_make_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582751600,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:2022",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:blk_queue_split",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:dm_wq_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582751600,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583029584,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:1995",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:blk_queue_split",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583029584,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583134352,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:1978",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:blk_queue_split",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583134352,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583190976,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:2138",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:blk_queue_split",
        "block/bounce.c:blk_queue_bounce",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583190976,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583367312,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:2259",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:blk_queue_split",
        "block/bounce.c:blk_queue_bounce",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583367312,
      "name": "generic_make_request",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583576688,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:2377",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:blk_queue_split",
        "block/bounce.c:blk_queue_bounce",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583576688,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1025
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
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583689280,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:1007",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:blk_queue_split",
        "block/bounce.c:blk_queue_bounce",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583689280,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1019
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583878112,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:994",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__blk_queue_split",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583878112,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583981072,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:1009",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__blk_queue_split",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583981072,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584370736,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:1101",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__blk_queue_split",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-crypto-fallback.c:blk_crypto_split_bio_if_needed",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584370736,
      "name": "generic_make_request.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
    },
    {
      "addr": 18446744071584371552,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495805432,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:1009",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495805432,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229157108,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:1009",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__blk_queue_split",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229157108,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289990320,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:1009",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289990320,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 996
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274943888,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:1009",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__blk_queue_split",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274943888,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583949808,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:1009",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__blk_queue_split",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/nvme/host/multipath.c:nvme_requeue_work",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583949808,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583886736,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:1009",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__blk_queue_split",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/nvme/host/multipath.c:nvme_requeue_work",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583886736,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583933568,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:1009",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__blk_queue_split",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583933568,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
```

```json
{
  "name": "generic_make_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584035168,
      "name": "generic_make_request",
      "external": true,
      "loc": "block/blk-core.c:1009",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_alloc_rescue",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-core.c:submit_bio",
        "block/blk-merge.c:__blk_queue_split",
        "block/bounce.c:__blk_queue_bounce",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "drivers/md/dm.c:dm_wq_work",
        "drivers/md/dm.c:dm_process_bio",
        "drivers/md/dm.c:__split_and_process_bio",
        "drivers/md/dm.c:__map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584035168,
      "name": "generic_make_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 818
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
blk_qc_t generic_make_request(struct bio * bio)
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
