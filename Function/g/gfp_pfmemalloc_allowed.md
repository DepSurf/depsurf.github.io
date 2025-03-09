# Function: <code>gfp_pfmemalloc_allowed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580495888,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:2959",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580495888,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580591392,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:3291",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580591392,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580658288,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:3396",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580658288,
      "name": "gfp_pfmemalloc_allowed",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580691184,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:3629",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580691184,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580777181,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:3769",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781312,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580912823,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:3903",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916928,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580988024,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4076",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992368,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581406455,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4243",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410768,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581467447,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4237",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471792,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581674284,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4355",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677840,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581722263,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4509",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725696,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581742888,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4558",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581747840,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582021032,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4734",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026368,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582447815,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4785",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453520,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582957295,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4894",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582963456,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583174380,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:3829",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "net/core/skbuff.c:kmalloc_reserve",
        "net/core/skbuff.c:kmalloc_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583180176,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583358146,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:3919",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "net/core/skbuff.c:kmalloc_reserve",
        "net/core/skbuff.c:kmalloc_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583363984,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492876372,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4237",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492880144,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226675192,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4237",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226680264,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286270284,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4237",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286274880,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272818316,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4237",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272821958,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581436295,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4237",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581440640,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581378679,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4237",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383024,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581427495,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4237",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431840,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool gfp_pfmemalloc_allowed(gfp_t gfp_mask)
```

```json
{
  "name": "gfp_pfmemalloc_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581491943,
      "name": "gfp_pfmemalloc_allowed",
      "external": true,
      "loc": "mm/page_alloc.c:4237",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581496336,
      "name": "gfp_pfmemalloc_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
