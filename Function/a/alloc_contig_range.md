# Function: <code>alloc_contig_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580514112,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:6681",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580514112,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 849
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580599872,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:7212",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580599872,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 920
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
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580666896,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:7264",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580666896,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 921
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
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580700128,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:7595",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580700128,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1043
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
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580785584,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:7619",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580785584,
      "name": "alloc_contig_range",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:7786",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923545,
      "name": "alloc_contig_range.cold.117",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580918944,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 915
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:8119",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999538,
      "name": "alloc_contig_range.cold.121",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580994576,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 942
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:8331",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581418577,
      "name": "alloc_contig_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581413360,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:8361",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581479528,
      "name": "alloc_contig_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581474400,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:8393",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581682016,
      "name": "alloc_contig_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581669216,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 735
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:8525",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591328896,
      "name": "alloc_contig_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581716704,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:8764",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591271004,
      "name": "alloc_contig_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071581736832,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 990
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
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:9027",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592204200,
      "name": "alloc_contig_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071582013664,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1125
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
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:9084",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593985227,
      "name": "alloc_contig_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582457360,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 706
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
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:9258",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596037723,
      "name": "alloc_contig_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582971440,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 706
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
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:6162",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596559956,
      "name": "alloc_contig_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583183280,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:6304",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597464371,
      "name": "alloc_contig_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583367392,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492885448,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:8361",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_gigantic_page",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492885448,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 980
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
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226684272,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:8361",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226684272,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1004
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
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286282384,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:8361",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286282384,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1212
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
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272825790,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:8361",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272825790,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 718
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:8361",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448376,
      "name": "alloc_contig_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581443248,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:8361",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390744,
      "name": "alloc_contig_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581385632,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:8361",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581439576,
      "name": "alloc_contig_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581434448,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int alloc_contig_range(long unsigned int start, long unsigned int end, unsigned int migratetype, gfp_t gfp_mask)
```

```json
{
  "name": "alloc_contig_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_contig_range",
      "external": true,
      "loc": "mm/page_alloc.c:8361",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_fresh_huge_page",
        "mm/cma.c:cma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504072,
      "name": "alloc_contig_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581498944,
      "name": "alloc_contig_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 959
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
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
