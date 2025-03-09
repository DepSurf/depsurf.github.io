# Function: <code>stable_tree_search</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580835418,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1148",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread"
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
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580961738,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1120",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread"
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
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581035700,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1149",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread"
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
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581083288,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1514",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581194773,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1525",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581339512,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1555",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581423447,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1553",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581534912,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1569",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581534912,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1483
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
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581599808,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1551",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581599808,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1483
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
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581815312,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1551",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581815312,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1463
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
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581863056,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1552",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863056,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1457
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
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581893520,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1550",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581893520,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1457
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
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582188224,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1546",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188224,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1457
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
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582649632,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1556",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582649632,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1917
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
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583175072,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1572",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583175072,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1974
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
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583391568,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1618",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391568,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2029
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
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583631840,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1817",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583631840,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2008
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
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493039960,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1551",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493039960,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1512
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
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226756972,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1551",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_do_scan"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286477952,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1551",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286477952,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2160
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
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272912484,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1551",
      "file": "mm/ksm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_do_scan"
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
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581568544,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1551",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568544,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1483
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
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510112,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1551",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510112,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1483
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
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581559856,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1551",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559856,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1483
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
struct page * stable_tree_search(struct page * page)
```

```json
{
  "name": "stable_tree_search",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581624832,
      "name": "stable_tree_search",
      "external": false,
      "loc": "mm/ksm.c:1551",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:cmp_and_merge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581624832,
      "name": "stable_tree_search",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1486
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct page * stable_tree_search(struct page * page)
```
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
struct page * stable_tree_search(struct page * page)
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
struct page * stable_tree_search(struct page * page)
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
