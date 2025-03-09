# Function: <code>page_counter_try_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914496,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:62",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914496,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581060800,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:62",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581060800,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136064,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:62",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136064,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581183232,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:62",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581183232,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581312400,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:63",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581312400,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581459360,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:99",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459360,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581543056,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:99",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543056,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652048,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:99",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652048,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581724576,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:99",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581724576,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581942400,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:94",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942400,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989744,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:94",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989744,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017584,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:98",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:obj_cgroup_charge_pages",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017584,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582320256,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:98",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:obj_cgroup_charge_pages",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582320256,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582812528,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:98",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812528,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583354976,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:97",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583354976,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583574304,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:97",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583574304,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583767712,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:97",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583767712,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493173616,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:99",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493173616,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226809052,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:99",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226809052,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286668560,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:99",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286668560,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272958406,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:99",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272958406,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581693312,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:99",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581693312,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581632336,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:99",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581632336,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684624,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:99",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684624,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
bool page_counter_try_charge(struct page_counter * counter, long unsigned int nr_pages, struct page_counter * * fail)
```

```json
{
  "name": "page_counter_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751504,
      "name": "page_counter_try_charge",
      "external": true,
      "loc": "mm/page_counter.c:99",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751504,
      "name": "page_counter_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
