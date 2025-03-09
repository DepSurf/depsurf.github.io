# Function: <code>cmp_and_merge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580834238,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:1434",
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
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580960550,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:1406",
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
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581035493,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:1435",
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
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581083128,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:1991",
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
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581194602,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2002",
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
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581339454,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2032",
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
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581423388,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2030",
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
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581536400,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2053",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581536400,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2760
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
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581601296,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2035",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581601296,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2760
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
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581818896,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2035",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581818896,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1321
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
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581866768,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2036",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581866768,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1381
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
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581897392,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2032",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581897392,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1365
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2028",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582192096,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
    },
    {
      "addr": 18446744071592216865,
      "name": "cmp_and_merge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2040",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582654496,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2008
    },
    {
      "addr": 18446744071593995695,
      "name": "cmp_and_merge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void cmp_and_merge_page(struct page * page, struct ksm_rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2056",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583177856,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2074
    },
    {
      "addr": 18446744071596045065,
      "name": "cmp_and_merge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void cmp_and_merge_page(struct page * page, struct ksm_rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2102",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583394144,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2209
    },
    {
      "addr": 18446744071596567499,
      "name": "cmp_and_merge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void cmp_and_merge_page(struct page * page, struct ksm_rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2301",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583634512,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2208
    },
    {
      "addr": 18446744071597473034,
      "name": "cmp_and_merge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493041472,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2035",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493041472,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2592
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
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226756920,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2035",
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
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286480112,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2035",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286480112,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3816
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
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272912448,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2035",
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
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570032,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2035",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570032,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2760
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
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581511600,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2035",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581511600,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2760
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
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581561344,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2035",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561344,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2760
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
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
```

```json
{
  "name": "cmp_and_merge_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581626320,
      "name": "cmp_and_merge_page",
      "external": false,
      "loc": "mm/ksm.c:2035",
      "file": "mm/ksm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581626320,
      "name": "cmp_and_merge_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2752
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
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rmap_item * rmap_item</code> ➡️ <code>struct ksm_rmap_item * rmap_item</code>
</li>
</ul>
</details>
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
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
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
void cmp_and_merge_page(struct page * page, struct rmap_item * rmap_item)
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
