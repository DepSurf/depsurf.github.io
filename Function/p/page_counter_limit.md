# Function: <code>page_counter_limit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int page_counter_limit(struct page_counter * counter, long unsigned int limit)
```

```json
{
  "name": "page_counter_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914720,
      "name": "page_counter_limit",
      "external": true,
      "loc": "mm/page_counter.c:134",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:memcg_activate_kmem",
        "mm/memcontrol.c:memcg_update_kmem_limit",
        "mm/memcontrol.c:mem_cgroup_resize_limit",
        "mm/memcontrol.c:mem_cgroup_resize_memsw_limit",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "net/ipv4/tcp_memcontrol.c:tcp_cgroup_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914720,
      "name": "page_counter_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int page_counter_limit(struct page_counter * counter, long unsigned int limit)
```

```json
{
  "name": "page_counter_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581061024,
      "name": "page_counter_limit",
      "external": true,
      "loc": "mm/page_counter.c:134",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581061024,
      "name": "page_counter_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int page_counter_limit(struct page_counter * counter, long unsigned int limit)
```

```json
{
  "name": "page_counter_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136288,
      "name": "page_counter_limit",
      "external": true,
      "loc": "mm/page_counter.c:134",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136288,
      "name": "page_counter_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int page_counter_limit(struct page_counter * counter, long unsigned int limit)
```

```json
{
  "name": "page_counter_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581183472,
      "name": "page_counter_limit",
      "external": true,
      "loc": "mm/page_counter.c:134",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581183472,
      "name": "page_counter_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int page_counter_limit(struct page_counter * counter, long unsigned int limit)
```

```json
{
  "name": "page_counter_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581312640,
      "name": "page_counter_limit",
      "external": true,
      "loc": "mm/page_counter.c:135",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_css_reset",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_write",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581312640,
      "name": "page_counter_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int page_counter_limit(struct page_counter * counter, long unsigned int limit)
```
</details>
</li>
</ul>
