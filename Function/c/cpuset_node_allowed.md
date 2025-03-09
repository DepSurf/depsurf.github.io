# Function: <code>cpuset_node_allowed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuset_node_allowed",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580487939,
      "name": "cpuset_node_allowed",
      "external": false,
      "loc": "include/linux/cpuset.h:53",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580508167,
      "name": "cpuset_node_allowed",
      "external": false,
      "loc": "include/linux/cpuset.h:53",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559923,
      "name": "cpuset_node_allowed",
      "external": false,
      "loc": "include/linux/cpuset.h:53",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580797512,
      "name": "cpuset_node_allowed",
      "external": false,
      "loc": "include/linux/cpuset.h:53",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580855027,
      "name": "cpuset_node_allowed",
      "external": false,
      "loc": "include/linux/cpuset.h:53",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:___slab_alloc"
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581158512,
      "name": "cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:4067",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/hugetlb.c:dequeue_hugetlb_folio_nodemask",
        "mm/slub.c:get_any_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581158512,
      "name": "cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
bool cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581264016,
      "name": "cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:4908",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/slub.c:get_any_partial",
        "mm/hugetlb.c:dequeue_hugetlb_folio_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264016,
      "name": "cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
bool cpuset_node_allowed(int node, gfp_t gfp_mask)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
