# Function: <code>kmem_cache_free_bulk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache * orig_s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860624,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:2890",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860624,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 687
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
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580988224,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3055",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580988224,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 751
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
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581062016,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3077",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062016,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581109248,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3074",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109248,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581214832,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3087",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581214832,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 783
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581369488,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3068",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369488,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581454128,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3118",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581454128,
      "name": "kmem_cache_free_bulk",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581570176,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3129",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_state_end",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570176,
      "name": "kmem_cache_free_bulk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1097
    },
    {
      "addr": 18446744071581579715,
      "name": "kmem_cache_free_bulk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071581571280,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581635312,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3127",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_state_end",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635312,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1204
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
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581853328,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3185",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:kfree_rcu_work",
        "fs/io_uring.c:io_submit_sqes",
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581853328,
      "name": "kmem_cache_free_bulk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071581853648,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581901360,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3256",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:kfree_rcu_work",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_req_free_batch",
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901360,
      "name": "kmem_cache_free_bulk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
    },
    {
      "addr": 18446744071581902176,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581931904,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3288",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:kfree_rcu_work",
        "fs/io_uring.c:io_ring_ctx_free",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:__kfree_skb_defer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581931904,
      "name": "kmem_cache_free_bulk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 859
    },
    {
      "addr": 18446744071581932768,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3620",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:kfree_rcu_work",
        "fs/io_uring.c:io_ring_ctx_free",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:__kfree_skb_defer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582230320,
      "name": "kmem_cache_free_bulk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 828
    },
    {
      "addr": 18446744071592221398,
      "name": "kmem_cache_free_bulk.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446744071592221606,
      "name": "kmem_cache_free_bulk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071582231152,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3670",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:kfree_rcu_work",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:__kfree_skb_defer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582697088,
      "name": "kmem_cache_free_bulk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1181
    },
    {
      "addr": 18446744071594000380,
      "name": "kmem_cache_free_bulk.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071594000530,
      "name": "kmem_cache_free_bulk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071582698272,
      "name": "kmem_cache_free_bulk",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583222648,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3893",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_alloc_bulk"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:kfree_rcu_work",
        "mm/slub.c:__kmem_cache_alloc_bulk",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:__kfree_skb_defer",
        "lib/maple_tree.c:mas_destroy",
        "lib/maple_tree.c:mt_destroy_walk",
        "lib/maple_tree.c:mt_destroy_walk",
        "lib/maple_tree.c:mt_free_walk",
        "lib/maple_tree.c:mt_free_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583221312,
      "name": "kmem_cache_free_bulk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
    },
    {
      "addr": 18446744071583222080,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583441287,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3907",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_alloc_bulk"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:kvfree_rcu_bulk",
        "mm/slub.c:__kmem_cache_alloc_bulk",
        "net/core/skbuff.c:napi_skb_free_stolen_head",
        "net/core/skbuff.c:kfree_skb_list_reason",
        "net/core/skbuff.c:kfree_skb_list_reason",
        "lib/maple_tree.c:mas_destroy",
        "lib/maple_tree.c:mt_free_walk",
        "lib/maple_tree.c:mt_free_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439872,
      "name": "kmem_cache_free_bulk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
    },
    {
      "addr": 18446744071583440656,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583424560,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:4514",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:kvfree_rcu_bulk",
        "net/core/skbuff.c:napi_skb_cache_put",
        "net/core/skbuff.c:kfree_skb_list_reason",
        "net/core/skbuff.c:kfree_skb_list_reason",
        "lib/maple_tree.c:mas_destroy",
        "lib/maple_tree.c:mt_free_walk",
        "lib/maple_tree.c:mt_free_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583424560,
      "name": "kmem_cache_free_bulk.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
    },
    {
      "addr": 18446744071583425408,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493084192,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3127",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_state_end",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493084192,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226788896,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3127",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_state_end",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226788896,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1404
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
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286530432,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3127",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_state_end",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286530432,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1592
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
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272942312,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3127",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_state_end",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272942312,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1078
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
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581604048,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3127",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_state_end",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581604048,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1204
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
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581545392,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3127",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_state_end",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581545392,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1204
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
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581595360,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3127",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_state_end",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595360,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1204
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
void kmem_cache_free_bulk(struct kmem_cache * s, size_t size, void * * p)
```

```json
{
  "name": "kmem_cache_free_bulk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581661200,
      "name": "kmem_cache_free_bulk",
      "external": true,
      "loc": "mm/slub.c:3127",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_submit_state_end",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__kfree_skb_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661200,
      "name": "kmem_cache_free_bulk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1219
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kmem_cache * s</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kmem_cache * orig_s</code>
</li>
</ul>
</details>
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
