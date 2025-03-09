# Function: <code>release_pte_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580898267,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/huge_memory.c:2180",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581049678,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:480",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581133006,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:482",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581169456,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:484",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169456,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581297344,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:485",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581297344,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581444752,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:485",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444752,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581528224,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:504",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581528224,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581636960,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:504",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581636960,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581707984,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:516",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581707984,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581924144,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:544",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:__collapse_huge_page_copy",
        "mm/khugepaged.c:__collapse_huge_page_copy",
        "mm/khugepaged.c:release_pte_pages",
        "mm/khugepaged.c:release_pte_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924144,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581971616,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:559",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:release_pte_pages",
        "mm/khugepaged.c:release_pte_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581971616,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581999728,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:557",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581999728,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582301792,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:561",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301792,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582793168,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:552",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582793168,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583331680,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:493",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583331680,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
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
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583551042,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:503",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493154224,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:516",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493154224,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286643744,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:516",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286643744,
      "name": "release_pte_page",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581676720,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:516",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581676720,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581616176,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:516",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581616176,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668032,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:516",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668032,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void release_pte_page(struct page * page)
```

```json
{
  "name": "release_pte_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581734400,
      "name": "release_pte_page",
      "external": false,
      "loc": "mm/khugepaged.c:516",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581734400,
      "name": "release_pte_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void release_pte_page(struct page * page)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void release_pte_page(struct page * page)
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
void release_pte_page(struct page * page)
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
void release_pte_page(struct page * page)
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
