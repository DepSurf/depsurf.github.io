# Function: <code>__cpuset_node_allowed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014352,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cpuset.c:2527",
      "file": "kernel/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014352,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046768,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cpuset.c:2548",
      "file": "kernel/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046768,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580086176,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cpuset.c:2548",
      "file": "kernel/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086176,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580091952,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:2548",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091952,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580144992,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:2552",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144992,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204672,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:2553",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204672,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580256976,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3361",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256976,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580307904,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3329",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307904,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580356768,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3417",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356768,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580429744,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3419",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:shrink_zones",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:get_any_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580429744,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580417296,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3442",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:shrink_zones",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:get_any_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580417296,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580420080,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3442",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:get_any_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420080,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580583392,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3524",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:get_any_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580583392,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580784480,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3570",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:get_any_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784480,
      "name": "__cpuset_node_allowed",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068160,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3875",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:constrained_alloc",
        "mm/vmscan.c:wakeup_kswapd",
        "mm/page_alloc.c:__alloc_pages_bulk",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:get_any_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068160,
      "name": "__cpuset_node_allowed",
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491615840,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3417",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491615840,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225572652,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3417",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225572652,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284608496,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3417",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284608496,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272017678,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3417",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/page_alloc.c:get_page_from_freelist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272017678,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580325568,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3417",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580325568,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580272832,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3417",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580272832,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580316816,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3417",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580316816,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
```

```json
{
  "name": "__cpuset_node_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580371712,
      "name": "__cpuset_node_allowed",
      "external": true,
      "loc": "kernel/cgroup/cpuset.c:3417",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:wakeup_kswapd",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/hugetlb.c:dequeue_huge_page_nodemask",
        "mm/slub.c:___slab_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580371712,
      "name": "__cpuset_node_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
bool __cpuset_node_allowed(int node, gfp_t gfp_mask)
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
