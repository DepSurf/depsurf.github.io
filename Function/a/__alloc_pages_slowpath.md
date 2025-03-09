# Function: <code>__alloc_pages_slowpath</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580510338,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:2970",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580591520,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:3402",
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
      "addr": 18446744071580591520,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2644
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580658400,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:3519",
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
      "addr": 18446744071580658400,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2969
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580691296,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:3781",
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
      "addr": 18446744071580691296,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3621
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580776656,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:3909",
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
      "addr": 18446744071580776656,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3665
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580912400,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4043",
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
      "addr": 18446744071580912400,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3540
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580987536,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4216",
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
      "addr": 18446744071580987536,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3742
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581405984,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4383",
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
      "addr": 18446744071581405984,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3619
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581466976,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4377",
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
      "addr": 18446744071581466976,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3652
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581673920,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4495",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581673920,
      "name": "__alloc_pages_slowpath.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2777
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
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581721904,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4649",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721904,
      "name": "__alloc_pages_slowpath.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2582
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
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581742528,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4698",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742528,
      "name": "__alloc_pages_slowpath.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2571
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582020672,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4874",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020672,
      "name": "__alloc_pages_slowpath.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2614
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4906",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582447504,
      "name": "__alloc_pages_slowpath.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2472
    },
    {
      "addr": 18446744071593982083,
      "name": "__alloc_pages_slowpath.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:5015",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582956976,
      "name": "__alloc_pages_slowpath.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2585
    },
    {
      "addr": 18446744071596037600,
      "name": "__alloc_pages_slowpath.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:3950",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583174080,
      "name": "__alloc_pages_slowpath.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2425
    },
    {
      "addr": 18446744071596559833,
      "name": "__alloc_pages_slowpath.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4040",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583357824,
      "name": "__alloc_pages_slowpath.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2534
    },
    {
      "addr": 18446744071597464232,
      "name": "__alloc_pages_slowpath.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492875976,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4377",
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
      "addr": 18446603336492875976,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2940
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226674732,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4377",
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
      "addr": 3226674732,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4112
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286269712,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4377",
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
      "addr": 13835058055286269712,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3748
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272817954,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4377",
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
      "addr": 18446743936272817954,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2796
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581435824,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4377",
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
      "addr": 18446744071581435824,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3652
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581378208,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4377",
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
      "addr": 18446744071581378208,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3652
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581427024,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4377",
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
      "addr": 18446744071581427024,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3652
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
```

```json
{
  "name": "__alloc_pages_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581491472,
      "name": "__alloc_pages_slowpath",
      "external": false,
      "loc": "mm/page_alloc.c:4377",
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
      "addr": 18446744071581491472,
      "name": "__alloc_pages_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3697
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
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct page * __alloc_pages_slowpath(gfp_t gfp_mask, unsigned int order, struct alloc_context * ac)
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
