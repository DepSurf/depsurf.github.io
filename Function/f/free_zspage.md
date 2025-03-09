# Function: <code>free_zspage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void free_zspage(struct page * first_page)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962720,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:886",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962720,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581121312,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1014",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121312,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581196416,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1014",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581196416,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581243936,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1006",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581243936,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581375616,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1010",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581375616,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581525520,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:993",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581525520,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581608112,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:980",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581608112,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581719328,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:970",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581719328,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581792784,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:967",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792784,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582016512,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:967",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582016512,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582064992,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:960",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064992,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582090187,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:960",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free"
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
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582402771,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:960",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582910608,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:952",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582910608,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583464896,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:1051",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583464896,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583682032,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:884",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583682032,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583876544,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:879",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583876544,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493254200,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:967",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493254200,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226866744,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:967",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226866744,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286782192,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:967",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286782192,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273012226,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:967",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273012226,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581761520,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:967",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761520,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581700144,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:967",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581700144,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581752832,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:967",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752832,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```

```json
{
  "name": "free_zspage",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581824592,
      "name": "free_zspage",
      "external": false,
      "loc": "mm/zsmalloc.c:967",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824592,
      "name": "free_zspage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
<code>struct zs_pool * pool</code>
</li>
<li>
<b>Param added. </b>
<code>struct size_class * class</code>
</li>
<li>
<b>Param added. </b>
<code>struct zspage * zspage</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * first_page</code>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void free_zspage(struct zs_pool * pool, struct size_class * class, struct zspage * zspage)
```
</details>
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
