# Function: <code>wake_all_kswapds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580512297,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:2901",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580575344,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:3239",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580575344,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void wake_all_kswapds(unsigned int order, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580641760,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:3344",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641760,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void wake_all_kswapds(unsigned int order, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580674192,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:3577",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674192,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void wake_all_kswapds(unsigned int order, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580759552,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:3680",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759552,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580895392,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:3812",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580895392,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580970208,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:3982",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580970208,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581388064,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4149",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581388064,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581449008,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4143",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581449008,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581655120,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4258",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581655120,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581702800,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4414",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702800,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581724416,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4463",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581724416,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581997792,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4639",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581997792,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582421392,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4687",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582421392,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582928688,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4796",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582928688,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583145568,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:3724",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583145568,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583328496,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:3814",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583328496,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492855504,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4143",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492855504,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226656188,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4143",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226656188,
      "name": "wake_all_kswapds",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286244736,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4143",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286244736,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272802976,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4143",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272802976,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581417856,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4143",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581417856,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581360368,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4143",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581360368,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581409056,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4143",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581409056,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void wake_all_kswapds(unsigned int order, gfp_t gfp_mask, const struct alloc_context * ac)
```

```json
{
  "name": "wake_all_kswapds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581473152,
      "name": "wake_all_kswapds",
      "external": false,
      "loc": "mm/page_alloc.c:4143",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581473152,
      "name": "wake_all_kswapds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void wake_all_kswapds(unsigned int order, const struct alloc_context * ac)
```
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_mask</code>
</li>
<li>
<b>Param reordered. </b>
<code>order, ac</code> ➡️ <code>order, gfp_mask, ac</code>
</li>
</ul>
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
