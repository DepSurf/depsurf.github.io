# Function: <code>set_max_huge_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int set_max_huge_pages(struct hstate * h, long unsigned int count, nodemask_t * nodes_allowed)
```

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580793568,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2141",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:nr_hugepages_store_common",
        "mm/hugetlb.c:hugetlb_sysctl_handler_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580793568,
      "name": "set_max_huge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1335
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
long unsigned int set_max_huge_pages(struct hstate * h, long unsigned int count, nodemask_t * nodes_allowed)
```

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917072,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2188",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917072,
      "name": "set_max_huge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1383
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580985388,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2294",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
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
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581031332,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2272",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
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
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581140951,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2280",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
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
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581282211,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2285",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
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
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581366803,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2279",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581475162,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2322",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581539294,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2424",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int set_max_huge_pages(struct hstate * h, long unsigned int count, int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749312,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2707",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749312,
      "name": "set_max_huge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
int set_max_huge_pages(struct hstate * h, long unsigned int count, int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581797440,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2660",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797440,
      "name": "set_max_huge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
int set_max_huge_pages(struct hstate * h, long unsigned int count, int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581825392,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2805",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581825392,
      "name": "set_max_huge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
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
int set_max_huge_pages(struct hstate * h, long unsigned int count, int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582114400,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:3088",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582114400,
      "name": "set_max_huge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1173
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
int set_max_huge_pages(struct hstate * h, long unsigned int count, int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582557072,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:3267",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557072,
      "name": "set_max_huge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1213
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
int set_max_huge_pages(struct hstate * h, long unsigned int count, int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:3431",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583079744,
      "name": "set_max_huge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1366
    },
    {
      "addr": 18446744071596041301,
      "name": "set_max_huge_pages.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int set_max_huge_pages(struct hstate * h, long unsigned int count, int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:3462",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583290288,
      "name": "set_max_huge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1345
    },
    {
      "addr": 18446744071596563466,
      "name": "set_max_huge_pages.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int set_max_huge_pages(struct hstate * h, long unsigned int count, int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:3691",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583519488,
      "name": "set_max_huge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1457
    },
    {
      "addr": 18446744071597468425,
      "name": "set_max_huge_pages.cold",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int set_max_huge_pages(struct hstate * h, long unsigned int count, int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492972392,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2424",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler_common",
        "mm/hugetlb.c:nr_hugepages_store_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492972392,
      "name": "set_max_huge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286391468,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2424",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272882972,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2424",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_sysctl_handler",
        "mm/hugetlb.c:nr_hugepages_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272882972,
      "name": "set_max_huge_pages.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581508030,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2424",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581450222,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2424",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581499342,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2424",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_max_huge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581565966,
      "name": "set_max_huge_pages",
      "external": false,
      "loc": "mm/hugetlb.c:2424",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__nr_hugepages_store_common"
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

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
long unsigned int set_max_huge_pages(struct hstate * h, long unsigned int count, nodemask_t * nodes_allowed)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int set_max_huge_pages(struct hstate * h, long unsigned int count, int nid, nodemask_t * nodes_allowed)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int set_max_huge_pages(struct hstate * h, long unsigned int count, int nid, nodemask_t * nodes_allowed)
```
</details>
</li>
</ul>
