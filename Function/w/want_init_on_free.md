# Function: <code>want_init_on_free</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool want_init_on_free()
```

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578855991,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2710",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ]
    },
    {
      "addr": 18446744071581389978,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2710",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581468547,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2710",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578855991,
      "name": "want_init_on_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool want_init_on_free()
```

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578855991,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ]
    },
    {
      "addr": 18446744071581450202,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581532595,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578855991,
      "name": "want_init_on_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool want_init_on_free()
```

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578860200,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2932",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:report_meminit",
        "init/main.c:report_meminit"
      ]
    },
    {
      "addr": 18446744071581661108,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2932",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740563,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2932",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586252037,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2932",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578860200,
      "name": "want_init_on_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool want_init_on_free()
```

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591237283,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2961",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ]
    },
    {
      "addr": 18446744071579972945,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2961",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:clear_or_poison_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720596,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2961",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788888,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2961",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586369765,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2961",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591237283,
      "name": "want_init_on_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool want_init_on_free()
```

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591179955,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2959",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ]
    },
    {
      "addr": 18446744071579975475,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2959",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581747146,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2959",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816360,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2959",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586252101,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2959",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591179955,
      "name": "want_init_on_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool want_init_on_free()
```

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592036139,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3017",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ]
    },
    {
      "addr": 18446744071580106785,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3017",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582025283,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3017",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582102600,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3017",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586762533,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3017",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592036139,
      "name": "want_init_on_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool want_init_on_free()
```

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593801839,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3129",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ]
    },
    {
      "addr": 18446744071580246173,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3129",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412785,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3129",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582452166,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3129",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582542904,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3129",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588040741,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3129",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593801839,
      "name": "want_init_on_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627477635,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3321",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580444399,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3321",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582920337,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3321",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582961224,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3321",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058644,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3321",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589419205,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3321",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580514209,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3496",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619620718,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3496",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:mm_core_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583136494,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3496",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583178130,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3496",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:__free_pages_ok"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583270634,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3496",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589719109,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3496",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580574641,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3702",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages",
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621924862,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3702",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:mm_core_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583319614,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3702",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_node_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583361988,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3702",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:free_unref_page_prepare",
        "mm/page_alloc.c:__free_pages_ok"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583506554,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3702",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590056869,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:3702",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool want_init_on_free()
```

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490176628,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ]
    },
    {
      "addr": 18446603336492856688,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492962336,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490176628,
      "name": "want_init_on_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243249300,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 3226657540,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3226742944,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
bool want_init_on_free()
```

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282230160,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ]
    },
    {
      "addr": 13835058055286247936,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286377636,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282230160,
      "name": "want_init_on_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270601132,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272803862,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272873736,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool want_init_on_free()
```

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578855991,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ]
    },
    {
      "addr": 18446744071581419050,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501331,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578855991,
      "name": "want_init_on_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool want_init_on_free()
```

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578849034,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ]
    },
    {
      "addr": 18446744071581361562,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581443555,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578849034,
      "name": "want_init_on_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool want_init_on_free()
```

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578855991,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ]
    },
    {
      "addr": 18446744071581410250,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581492643,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578855991,
      "name": "want_init_on_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool want_init_on_free()
```

```json
{
  "name": "want_init_on_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578856039,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel"
      ]
    },
    {
      "addr": 18446744071581475322,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557651,
      "name": "want_init_on_free",
      "external": false,
      "loc": "include/linux/mm.h:2685",
      "file": "mm/dmapool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/dmapool.c:dma_pool_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578856039,
      "name": "want_init_on_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
bool want_init_on_free()
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool want_init_on_free()
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool want_init_on_free()
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
bool want_init_on_free()
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
