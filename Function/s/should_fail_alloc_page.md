# Function: <code>should_fail_alloc_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:2340",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:2700",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:2751",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:2934",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:2991",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:3095",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580968480,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:3209",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580968480,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386192,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:3374",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386192,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581447136,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:3365",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581447136,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652352,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:3476",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652352,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581699936,
      "name": "should_fail_alloc_page",
      "external": true,
      "loc": "mm/page_alloc.c:3591",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581699936,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581721648,
      "name": "should_fail_alloc_page",
      "external": true,
      "loc": "mm/page_alloc.c:3641",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721648,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581993840,
      "name": "should_fail_alloc_page",
      "external": true,
      "loc": "mm/page_alloc.c:3812",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993840,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582416848,
      "name": "should_fail_alloc_page",
      "external": true,
      "loc": "mm/page_alloc.c:3848",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582416848,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582924800,
      "name": "should_fail_alloc_page",
      "external": true,
      "loc": "mm/page_alloc.c:3933",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582924800,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583141200,
      "name": "should_fail_alloc_page",
      "external": true,
      "loc": "mm/page_alloc.c:2849",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583141200,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583324320,
      "name": "should_fail_alloc_page",
      "external": true,
      "loc": "mm/page_alloc.c:2920",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages",
        "mm/page_alloc.c:__alloc_pages_bulk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583324320,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492853592,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:3365",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask",
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492853592,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226657060,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:3365",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226657060,
      "name": "should_fail_alloc_page.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286241616,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:3365",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286241616,
      "name": "should_fail_alloc_page",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272803358,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:3365",
      "file": "mm/page_alloc.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272803358,
      "name": "should_fail_alloc_page.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581415984,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:3365",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415984,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581358496,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:3365",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358496,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581407184,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:3365",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407184,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```

```json
{
  "name": "should_fail_alloc_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581471280,
      "name": "should_fail_alloc_page",
      "external": false,
      "loc": "mm/page_alloc.c:3365",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471280,
      "name": "should_fail_alloc_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
```
</details>
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
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
bool should_fail_alloc_page(gfp_t gfp_mask, unsigned int order)
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
