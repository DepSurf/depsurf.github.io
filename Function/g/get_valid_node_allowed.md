# Function: <code>get_valid_node_allowed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580789498,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:949",
      "file": "mm/hugetlb.c",
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
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580912762,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:969",
      "file": "mm/hugetlb.c",
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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580980874,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:969",
      "file": "mm/hugetlb.c",
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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581028122,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:989",
      "file": "mm/hugetlb.c",
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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581137242,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:990",
      "file": "mm/hugetlb.c",
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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581277754,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:982",
      "file": "mm/hugetlb.c",
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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581360698,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:982",
      "file": "mm/hugetlb.c",
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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581469712,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:992",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469712,
      "name": "get_valid_node_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581533728,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:993",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581533728,
      "name": "get_valid_node_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581749543,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:1158",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581797671,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:1183",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581826181,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:1193",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:hstate_next_node_to_alloc"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582115228,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:1207",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:hstate_next_node_to_alloc"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582555638,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:1255",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583061360,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:1419",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583061360,
      "name": "get_valid_node_allowed",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583271568,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:1416",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271568,
      "name": "get_valid_node_allowed",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583507488,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:1454",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_hugetlb_folio",
        "mm/hugetlb.c:alloc_pool_huge_folio",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583507488,
      "name": "get_valid_node_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492966116,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:993",
      "file": "mm/hugetlb.c",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286379136,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:993",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286379136,
      "name": "get_valid_node_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272875480,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:993",
      "file": "mm/hugetlb.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581502464,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:993",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502464,
      "name": "get_valid_node_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581444768,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:993",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444768,
      "name": "get_valid_node_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581493776,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:993",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493776,
      "name": "get_valid_node_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
```

```json
{
  "name": "get_valid_node_allowed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581558784,
      "name": "get_valid_node_allowed",
      "external": false,
      "loc": "mm/hugetlb.c:993",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558784,
      "name": "get_valid_node_allowed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
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
int get_valid_node_allowed(int nid, nodemask_t * nodes_allowed)
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
