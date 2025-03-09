# Function: <code>has_extra_refcount</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool has_extra_refcount(struct page_state * ps, struct page * p, bool extra_pins)
```

```json
{
  "name": "has_extra_refcount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582883080,
      "name": "has_extra_refcount",
      "external": false,
      "loc": "mm/memory-failure.c:821",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_swapcache_clean"
      ],
      "caller_func": [
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_pagecache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880016,
      "name": "has_extra_refcount",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool has_extra_refcount(struct page_state * ps, struct page * p, bool extra_pins)
```

```json
{
  "name": "has_extra_refcount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583431239,
      "name": "has_extra_refcount",
      "external": false,
      "loc": "mm/memory-failure.c:883",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:me_swapcache_clean"
      ],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_pagecache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583428928,
      "name": "has_extra_refcount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
bool has_extra_refcount(struct page_state * ps, struct page * p, bool extra_pins)
```

```json
{
  "name": "has_extra_refcount",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583652951,
      "name": "has_extra_refcount",
      "external": false,
      "loc": "mm/memory-failure.c:980",
      "file": "mm/memory-failure.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:me_swapcache_clean"
      ],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_pagecache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583650512,
      "name": "has_extra_refcount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
bool has_extra_refcount(struct page_state * ps, struct page * p, bool extra_pins)
```

```json
{
  "name": "has_extra_refcount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583846384,
      "name": "has_extra_refcount",
      "external": false,
      "loc": "mm/memory-failure.c:979",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_swapcache_clean",
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_pagecache_clean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583846384,
      "name": "has_extra_refcount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool has_extra_refcount(struct page_state * ps, struct page * p, bool extra_pins)
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
