# Function: <code>page_poisoning_enabled</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool page_poisoning_enabled()
```

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581346565,
      "name": "page_poisoning_enabled",
      "external": true,
      "loc": "mm/page_poison.c:20",
      "file": "mm/page_poison.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346528,
      "name": "page_poisoning_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool page_poisoning_enabled()
```

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581430661,
      "name": "page_poisoning_enabled",
      "external": true,
      "loc": "mm/page_poison.c:25",
      "file": "mm/page_poison.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "drivers/virtio/virtio_balloon.c:virtballoon_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581430624,
      "name": "page_poisoning_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool page_poisoning_enabled()
```

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581543621,
      "name": "page_poisoning_enabled",
      "external": true,
      "loc": "mm/page_poison.c:26",
      "file": "mm/page_poison.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:want_init_on_free",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/dmapool.c:dma_pool_free",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "net/core/sock.c:sk_prot_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543584,
      "name": "page_poisoning_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool page_poisoning_enabled()
```

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581608517,
      "name": "page_poisoning_enabled",
      "external": true,
      "loc": "mm/page_poison.c:26",
      "file": "mm/page_poison.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:want_init_on_free",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/dmapool.c:dma_pool_free",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "net/core/sock.c:sk_prot_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581608480,
      "name": "page_poisoning_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool page_poisoning_enabled()
```

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581823573,
      "name": "page_poisoning_enabled",
      "external": true,
      "loc": "mm/page_poison.c:26",
      "file": "mm/page_poison.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": [
        "init/main.c:report_meminit",
        "init/main.c:want_init_on_free",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/dmapool.c:dma_pool_free",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "net/core/sock.c:sk_prot_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581823392,
      "name": "page_poisoning_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579972936,
      "name": "page_poisoning_enabled",
      "external": false,
      "loc": "include/linux/mm.h:2922",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581709186,
      "name": "page_poisoning_enabled",
      "external": false,
      "loc": "include/linux/mm.h:2922",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579975466,
      "name": "page_poisoning_enabled",
      "external": false,
      "loc": "include/linux/mm.h:2919",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581729989,
      "name": "page_poisoning_enabled",
      "external": false,
      "loc": "include/linux/mm.h:2919",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:init_mem_debugging_and_hardening"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580106764,
      "name": "page_poisoning_enabled",
      "external": false,
      "loc": "include/linux/mm.h:2977",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582003829,
      "name": "page_poisoning_enabled",
      "external": false,
      "loc": "include/linux/mm.h:2977",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:init_mem_debugging_and_hardening"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580246152,
      "name": "page_poisoning_enabled",
      "external": false,
      "loc": "include/linux/mm.h:3089",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582428213,
      "name": "page_poisoning_enabled",
      "external": false,
      "loc": "include/linux/mm.h:3089",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:init_mem_debugging_and_hardening"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580444188,
      "name": "page_poisoning_enabled",
      "external": false,
      "loc": "include/linux/mm.h:3281",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627860277,
      "name": "page_poisoning_enabled",
      "external": false,
      "loc": "include/linux/mm.h:3281",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:init_mem_debugging_and_hardening"
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
  "name": "page_poisoning_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580514188,
      "name": "page_poisoning_enabled",
      "external": false,
      "loc": "include/linux/mm.h:3456",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619620412,
      "name": "page_poisoning_enabled",
      "external": false,
      "loc": "include/linux/mm.h:3456",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_core_init"
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
  "name": "page_poisoning_enabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580574620,
      "name": "page_poisoning_enabled",
      "external": false,
      "loc": "include/linux/mm.h:3662",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621924556,
      "name": "page_poisoning_enabled",
      "external": false,
      "loc": "include/linux/mm.h:3662",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:mm_core_init"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool page_poisoning_enabled()
```

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493050596,
      "name": "page_poisoning_enabled",
      "external": true,
      "loc": "mm/page_poison.c:26",
      "file": "mm/page_poison.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:want_init_on_free",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/dmapool.c:dma_pool_free",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "net/core/sock.c:sk_prot_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493050528,
      "name": "page_poisoning_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool page_poisoning_enabled()
```

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226763772,
      "name": "page_poisoning_enabled",
      "external": true,
      "loc": "mm/page_poison.c:26",
      "file": "mm/page_poison.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/dmapool.c:dma_pool_free",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "net/core/sock.c:sk_prot_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226763716,
      "name": "page_poisoning_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
bool page_poisoning_enabled()
```

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286488896,
      "name": "page_poisoning_enabled",
      "external": true,
      "loc": "mm/page_poison.c:26",
      "file": "mm/page_poison.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:want_init_on_free",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/dmapool.c:dma_pool_free",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "net/core/sock.c:sk_prot_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286488848,
      "name": "page_poisoning_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
bool page_poisoning_enabled()
```

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272918248,
      "name": "page_poisoning_enabled",
      "external": true,
      "loc": "mm/page_poison.c:26",
      "file": "mm/page_poison.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "init/main.c:start_kernel",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/dmapool.c:dma_pool_free",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "net/core/sock.c:sk_prot_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272918180,
      "name": "page_poisoning_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
bool page_poisoning_enabled()
```

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581577253,
      "name": "page_poisoning_enabled",
      "external": true,
      "loc": "mm/page_poison.c:26",
      "file": "mm/page_poison.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:want_init_on_free",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/dmapool.c:dma_pool_free",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "net/core/sock.c:sk_prot_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581577216,
      "name": "page_poisoning_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool page_poisoning_enabled()
```

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581518821,
      "name": "page_poisoning_enabled",
      "external": true,
      "loc": "mm/page_poison.c:26",
      "file": "mm/page_poison.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:want_init_on_free",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/dmapool.c:dma_pool_free",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "net/core/sock.c:sk_prot_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518784,
      "name": "page_poisoning_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool page_poisoning_enabled()
```

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581568565,
      "name": "page_poisoning_enabled",
      "external": true,
      "loc": "mm/page_poison.c:26",
      "file": "mm/page_poison.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:want_init_on_free",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/dmapool.c:dma_pool_free",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "net/core/sock.c:sk_prot_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568528,
      "name": "page_poisoning_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool page_poisoning_enabled()
```

```json
{
  "name": "page_poisoning_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581633557,
      "name": "page_poisoning_enabled",
      "external": true,
      "loc": "mm/page_poison.c:26",
      "file": "mm/page_poison.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": [
        "init/main.c:start_kernel",
        "init/main.c:want_init_on_free",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/dmapool.c:dma_pool_free",
        "mm/dmapool.c:dma_pool_alloc",
        "drivers/virtio/virtio_balloon.c:virtballoon_validate",
        "net/core/sock.c:sk_prot_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581633520,
      "name": "page_poisoning_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool page_poisoning_enabled()
```
</details>
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
bool page_poisoning_enabled()
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
