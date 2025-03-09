# Function: <code>page_counter_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914448,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:36",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline",
        "net/core/sock.c:__sk_mem_schedule",
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914448,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581060752,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:36",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581060752,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136016,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:36",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136016,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581183184,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:36",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581183184,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581312352,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:37",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581312352,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581459264,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:72",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459264,
      "name": "page_counter_charge",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581542960,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:72",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581542960,
      "name": "page_counter_charge",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581651952,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:72",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651952,
      "name": "page_counter_charge",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581724480,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:72",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581724480,
      "name": "page_counter_charge",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581942320,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:67",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942320,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989664,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:67",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989664,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017504,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:71",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:obj_cgroup_charge_pages",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017504,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582320176,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:71",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:obj_cgroup_charge_pages",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582320176,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582812416,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:71",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812416,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583354848,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:70",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583354848,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583574176,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:70",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583574176,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583767584,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:70",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_replace_folio",
        "mm/memcontrol.c:mem_cgroup_replace_folio",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583767584,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493173496,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:72",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493173496,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226808944,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:72",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226808944,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286668400,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:72",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286668400,
      "name": "page_counter_charge",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272958322,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:72",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272958322,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581693216,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:72",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581693216,
      "name": "page_counter_charge",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581632240,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:72",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581632240,
      "name": "page_counter_charge",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684528,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:72",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684528,
      "name": "page_counter_charge",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void page_counter_charge(struct page_counter * counter, long unsigned int nr_pages)
```

```json
{
  "name": "page_counter_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581751408,
      "name": "page_counter_charge",
      "external": true,
      "loc": "mm/page_counter.c:72",
      "file": "mm/page_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:__memcg_kmem_charge_memcg",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751408,
      "name": "page_counter_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
