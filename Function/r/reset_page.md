# Function: <code>reset_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580962759,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:876",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:free_zspage",
        "mm/zsmalloc.c:free_zspage",
        "mm/zsmalloc.c:free_zspage"
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581114608,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:937",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581114608,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581189696,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:937",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189696,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237840,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:930",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237840,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369360,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:934",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369360,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581519264,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:917",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519264,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581605152,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:917",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581605152,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716400,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:907",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716400,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581789856,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:904",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789856,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582013088,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:904",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582013088,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582061568,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:897",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582061568,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582086352,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:897",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086352,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582399024,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:897",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582399024,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582916142,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:890",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
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
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583470609,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:953",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
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
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583687584,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:823",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
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
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583880401,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:818",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493253760,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:904",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493253760,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226862268,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:904",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226862268,
      "name": "reset_page",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286777168,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:904",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286777168,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273015876,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:904",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758592,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:904",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758592,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581697216,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:904",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697216,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749904,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:904",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749904,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void reset_page(struct page * page)
```

```json
{
  "name": "reset_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581818224,
      "name": "reset_page",
      "external": false,
      "loc": "mm/zsmalloc.c:904",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581818224,
      "name": "reset_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void reset_page(struct page * page)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void reset_page(struct page * page)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void reset_page(struct page * page)
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
