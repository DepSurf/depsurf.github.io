# Function: <code>ksize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
size_t ksize(const void * object)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580846672,
      "name": "ksize",
      "external": true,
      "loc": "mm/slub.c:3605",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:__krealloc",
        "mm/slab_common.c:krealloc",
        "fs/coredump.c:expand_corename",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846672,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
size_t ksize(const void * object)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580968768,
      "name": "ksize",
      "external": true,
      "loc": "mm/slub.c:3828",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "fs/coredump.c:expand_corename",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580968768,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
size_t ksize(const void * object)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581042544,
      "name": "ksize",
      "external": true,
      "loc": "mm/slub.c:3850",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "fs/coredump.c:expand_corename",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042544,
      "name": "ksize",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
size_t ksize(const void * object)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581089760,
      "name": "ksize",
      "external": true,
      "loc": "mm/slub.c:3855",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "fs/coredump.c:expand_corename",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581089760,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
size_t ksize(const void * object)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581201952,
      "name": "ksize",
      "external": true,
      "loc": "mm/slub.c:3871",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "fs/coredump.c:expand_corename",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581201952,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
size_t ksize(const void * object)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346976,
      "name": "ksize",
      "external": true,
      "loc": "mm/slub.c:3880",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "fs/dcache.c:__d_alloc",
        "fs/dcache.c:__d_free_external_name",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346976,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
size_t ksize(const void * object)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581431072,
      "name": "ksize",
      "external": true,
      "loc": "mm/slub.c:3932",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431072,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581207424,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1698",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581207424,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581266224,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1762",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266224,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581456868,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1748",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc"
      ],
      "caller_func": [
        "fs/coredump.c:format_corename",
        "fs/coredump.c:cn_vprintf",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455024,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581498325,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1155",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kfree_sensitive",
        "mm/slab_common.c:krealloc"
      ],
      "caller_func": [
        "fs/coredump.c:format_corename",
        "fs/coredump.c:cn_vprintf",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/base/devres.c:devm_krealloc",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498288,
      "name": "ksize",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581519205,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1252",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kfree_sensitive"
      ],
      "caller_func": [
        "fs/coredump.c:cn_vprintf",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/base/devres.c:devm_krealloc",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__build_skb_around"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519168,
      "name": "ksize",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581782789,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1286",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kfree_sensitive"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:copy_array",
        "fs/coredump.c:cn_vprintf",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/base/devres.c:devm_krealloc",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__build_skb_around"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780992,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582170133,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1263",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kfree_sensitive"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd",
        "kernel/bpf/verifier.c:copy_array",
        "fs/coredump.c:cn_vprintf",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/base/devres.c:devm_krealloc",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__build_skb_around"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582167808,
      "name": "ksize",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582655925,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1431",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kfree_sensitive",
        "mm/slab_common.c:krealloc"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:copy_array",
        "kernel/bpf/memalloc.c:bpf_mem_free",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/base/devres.c:devm_krealloc",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:slab_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655824,
      "name": "ksize",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582866037,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1439",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kfree_sensitive",
        "mm/slab_common.c:krealloc"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:copy_array",
        "kernel/bpf/memalloc.c:bpf_mem_free",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/base/devres.c:devm_krealloc",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:slab_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582865936,
      "name": "ksize",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583037253,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1253",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kfree_sensitive",
        "mm/slab_common.c:krealloc"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:copy_array",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_commit_ok",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/base/devres.c:devm_krealloc",
        "drivers/gpu/drm/drm_managed.c:drmm_add_final_kfree",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:slab_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583037152,
      "name": "ksize",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492667976,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1762",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492667976,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226510104,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1762",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "fs/coredump.c:expand_corename",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226510104,
      "name": "ksize",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285994416,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1762",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285994416,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272678778,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1762",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:__build_skb",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272678778,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581235072,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1762",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581235072,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581181744,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1762",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581181744,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581226272,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1762",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581226272,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
size_t ksize(const void * objp)
```

```json
{
  "name": "ksize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581290288,
      "name": "ksize",
      "external": true,
      "loc": "mm/slab_common.c:1762",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kzfree",
        "mm/slab_common.c:krealloc",
        "mm/slab_common.c:__krealloc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/memory.c:tomoyo_memory_ok",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581290288,
      "name": "ksize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void * objp</code>
</li>
<li>
<b>Param removed. </b>
<code>const void * object</code>
</li>
</ul>
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
