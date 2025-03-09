# Function: <code>migrate_page_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580811580,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:924",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
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
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580937641,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:956",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
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
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581009381,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:958",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581057382,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:886",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581165920,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:928",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165920,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581309232,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:903",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581309232,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581390144,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:943",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390144,
      "name": "migrate_page_add",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581502048,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:970",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502048,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581566416,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:971",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566416,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581778240,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:1040",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581778240,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581825488,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:1039",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581825488,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581855472,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:1049",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855472,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582149504,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:1020",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582149504,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582605760,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:1016",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582605760,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583130032,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:1030",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583130032,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 471
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
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
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493003280,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:971",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493003280,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286430640,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:971",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286430640,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581535152,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:971",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581535152,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581476912,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:971",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581476912,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581526464,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:971",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581526464,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```

```json
{
  "name": "migrate_page_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591744,
      "name": "migrate_page_add",
      "external": false,
      "loc": "mm/mempolicy.c:971",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591744,
      "name": "migrate_page_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
```
</details>
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
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
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
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
int migrate_page_add(struct page * page, struct list_head * pagelist, long unsigned int flags)
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
