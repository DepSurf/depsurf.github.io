# Function: <code>dissolve_free_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580796629,
      "name": "dissolve_free_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1415",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:dissolve_free_huge_pages"
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
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580920122,
      "name": "dissolve_free_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1442",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:dissolve_free_huge_pages"
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
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580988336,
      "name": "dissolve_free_huge_page",
      "external": false,
      "loc": "mm/hugetlb.c:1444",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:dissolve_free_huge_pages"
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581034752,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1462",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581034752,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581144496,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1468",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144496,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287616,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1485",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287616,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581370528,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1486",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581370528,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581481328,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1521",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581481328,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581545744,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1601",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581545744,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581756111,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1846",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:dissolve_free_huge_pages"
      ],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581748640,
      "name": "dissolve_free_huge_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071581755968,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581803904,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1794",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803904,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831104,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1743",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831104,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1952",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:__page_handle_poison"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592212206,
      "name": "dissolve_free_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071582120400,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2064",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:__page_handle_poison"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593990788,
      "name": "dissolve_free_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071582565744,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1025
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2277",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:__page_handle_poison"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596041573,
      "name": "dissolve_free_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583084624,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2304",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:__page_handle_poison"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596563764,
      "name": "dissolve_free_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583295088,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:2415",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:__page_handle_poison"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597469142,
      "name": "dissolve_free_huge_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583531392,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492979528,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1601",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492979528,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286399792,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1601",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286399792,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272885300,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1601",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272885300,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581514480,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1601",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581514480,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581456672,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1601",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456672,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581505792,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1601",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581505792,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int dissolve_free_huge_page(struct page * page)
```

```json
{
  "name": "dissolve_free_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581570784,
      "name": "dissolve_free_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:1601",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:dissolve_free_huge_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570784,
      "name": "dissolve_free_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
int dissolve_free_huge_page(struct page * page)
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
int dissolve_free_huge_page(struct page * page)
```
</details>
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
