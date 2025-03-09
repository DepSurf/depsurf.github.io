# Function: <code>page_counter_uncharge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914656,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:116",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:cancel_charge",
        "mm/memcontrol.c:cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "net/core/sock.c:__sk_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914656,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581060960,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:116",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:cancel_charge",
        "mm/memcontrol.c:cancel_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581060960,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136224,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:116",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:cancel_charge",
        "mm/memcontrol.c:cancel_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136224,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581183408,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:116",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581183408,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581312576,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:117",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581312576,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581459568,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:155",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459568,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581543264,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:155",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543264,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652224,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:155",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652224,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581724752,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:155",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581724752,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581942576,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:151",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:drain_stock",
        "mm/memcontrol.c:drain_stock",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942576,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989920,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:151",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:drain_stock",
        "mm/memcontrol.c:drain_stock",
        "mm/memcontrol.c:obj_cgroup_release",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989920,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017760,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:155",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:obj_cgroup_charge_pages",
        "mm/memcontrol.c:obj_cgroup_charge_pages",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:drain_stock",
        "mm/memcontrol.c:drain_stock",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017760,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582320432,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:155",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:obj_cgroup_charge_pages",
        "mm/memcontrol.c:obj_cgroup_charge_pages",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582320432,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582812736,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:154",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812736,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583355200,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:153",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583355200,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583574528,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:153",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583574528,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583767936,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:153",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583767936,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493173904,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:155",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493173904,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226809272,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:155",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:drain_stock",
        "mm/memcontrol.c:drain_stock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226809272,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286668896,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:155",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286668896,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272958564,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:155",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272958564,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581693488,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:155",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581693488,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581632512,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:155",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581632512,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684800,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:155",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684800,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void page_counter_uncharge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_uncharge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751680,
      "name": "page_counter_uncharge",
      "external": true,
      "loc": "mm/page_counter.c:155",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:__memcg_kmem_uncharge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751680,
      "name": "page_counter_uncharge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
