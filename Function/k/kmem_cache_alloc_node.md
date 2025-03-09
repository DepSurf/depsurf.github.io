# Function: <code>kmem_cache_alloc_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857264,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2598",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:alloc_request_struct",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-ioc.c:create_task_io_context",
        "block/blk-ioc.c:ioc_create_icq",
        "block/cfq-iosched.c:cfq_get_queue",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857264,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580989440,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2727",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:alloc_request_struct",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "block/cfq-iosched.c:cfq_get_queue",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580989440,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063216,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2749",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:alloc_request_struct",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "block/cfq-iosched.c:cfq_get_queue",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063216,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581107312,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2746",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/slub.c:__kmem_cache_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:alloc_request_simple",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "block/cfq-iosched.c:cfq_get_queue",
        "drivers/scsi/scsi_lib.c:scsi_init_rq",
        "drivers/scsi/scsi_lib.c:scsi_init_request",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581107312,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581222224,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2759",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/slub.c:__kmem_cache_create",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:alloc_request_simple",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "block/cfq-iosched.c:cfq_get_queue",
        "drivers/scsi/scsi_lib.c:scsi_old_init_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222224,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581362752,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2742",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:alloc_request_simple",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "block/cfq-iosched.c:cfq_get_queue",
        "drivers/scsi/scsi_lib.c:scsi_old_init_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581362752,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581448032,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2792",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448032,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581561264,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2804",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561264,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581626288,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2800",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581626288,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581843248,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2858",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:init_kmem_cache_nodes",
        "block/blk-core.c:__blk_alloc_queue",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581843248,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 602
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581893920,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2926",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:init_kmem_cache_nodes",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581893920,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581925312,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2948",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:reserve_lbr_buffers",
        "kernel/fork.c:dup_task_struct",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/events/core.c:perf_event_alloc",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581925312,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226880,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:3247",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:reserve_lbr_buffers",
        "kernel/fork.c:dup_task_struct",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/events/core.c:perf_event_alloc",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226880,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582686592,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:3291",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:reserve_lbr_buffers",
        "kernel/fork.c:dup_task_struct",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/events/core.c:perf_event_alloc",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:init_kmem_cache_nodes",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:alloc_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582686592,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583214464,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:3495",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:reserve_lbr_buffers",
        "kernel/fork.c:dup_task_struct",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/events/core.c:perf_event_alloc",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:alloc_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583214464,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 902
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583432848,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:3513",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:reserve_lbr_buffers",
        "kernel/fork.c:dup_task_struct",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/events/core.c:perf_event_alloc",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:alloc_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:kmalloc_reserve",
        "net/core/skbuff.c:kmalloc_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583432848,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 943
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583412672,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:3901",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:reserve_lbr_buffers",
        "kernel/fork.c:dup_task_struct",
        "kernel/workqueue.c:alloc_and_link_pwqs",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/events/core.c:perf_event_alloc",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:kmem_cache_open",
        "mm/zswap.c:zswap_store",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:alloc_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:kmalloc_reserve",
        "net/core/skbuff.c:kmalloc_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412672,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 867
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493073280,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2800",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493073280,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224706360,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3224850844,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 3226646364,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226793152,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3229148320,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_alloc_queue_node"
      ],
      "caller_func": []
    },
    {
      "addr": 3229177428,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "block/blk-ioc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3232016204,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3234660044,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286516096,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2800",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/dtl.c:dtl_file_open",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286516096,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 920
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271383898,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271491476,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272791936,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272943994,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274937702,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_alloc_queue_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274962542,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "block/blk-ioc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276751732,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278214262,
      "name": "kmem_cache_alloc_node",
      "external": false,
      "loc": "include/linux/slab.h:425",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595024,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2800",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595024,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581536432,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2800",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581536432,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581586336,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2800",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586336,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 593
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
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```

```json
{
  "name": "kmem_cache_alloc_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652800,
      "name": "kmem_cache_alloc_node",
      "external": true,
      "loc": "mm/slub.c:2800",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/slub.c:kmem_cache_open",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-ioc.c:ioc_create_icq",
        "block/blk-ioc.c:create_task_io_context",
        "drivers/scsi/scsi_lib.c:scsi_mq_init_request",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652800,
      "name": "kmem_cache_alloc_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * kmem_cache_alloc_node(struct kmem_cache * s, gfp_t gfpflags, int node)
```
</details>
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
