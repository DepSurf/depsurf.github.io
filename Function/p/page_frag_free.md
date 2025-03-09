# Function: <code>page_frag_free</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580646384,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4018",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646384,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580678704,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4305",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580678704,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580763488,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4424",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:bq_flush_to_queue",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:__cpu_map_queue_destructor",
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580763488,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580901248,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4556",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901248,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980320,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4727",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980320,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581402992,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4894",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402992,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463984,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4912",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463984,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668608,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:5015",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668608,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581717984,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:5194",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717984,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581738352,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:5397",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_release_data",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581738352,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015296,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:5578",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015296,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441408,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:5633",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441408,
      "name": "page_frag_free",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582950144,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:5772",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582950144,
      "name": "page_frag_free",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583167200,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4700",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583167200,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583350688,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4789",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583350688,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492872232,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4912",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492872232,
      "name": "page_frag_free",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226671400,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4912",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226671400,
      "name": "page_frag_free",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286265264,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4912",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286265264,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272815236,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4912",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272815236,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581432832,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4912",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432832,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581375248,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4912",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581375248,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581424032,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4912",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581424032,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void page_frag_free(void * addr)
```

```json
{
  "name": "page_frag_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581488480,
      "name": "page_frag_free",
      "external": true,
      "loc": "mm/page_alloc.c:4912",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_free_head",
        "net/core/skbuff.c:__napi_alloc_skb",
        "net/core/skbuff.c:__netdev_alloc_skb",
        "net/core/xdp.c:__xdp_return",
        "net/xdp/xsk_queue.c:xskq_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581488480,
      "name": "page_frag_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void page_frag_free(void * addr)
```
</details>
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
