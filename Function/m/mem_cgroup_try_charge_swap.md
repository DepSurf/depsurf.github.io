# Function: <code>mem_cgroup_try_charge_swap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581091168,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:5905",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091168,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166384,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:5905",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166384,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581214144,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:5967",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581214144,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581344768,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:6073",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_writepage",
        "mm/swap_state.c:add_to_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344768,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581492416,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:6141",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581492416,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581578272,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:6472",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581578272,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581689440,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:6764",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581689440,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581762864,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7094",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581762864,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581982160,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:6951",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581982160,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582032480,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7202",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582032480,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582059232,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7071",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059232,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582090951,
      "name": "mem_cgroup_try_charge_swap",
      "external": false,
      "loc": "include/linux/swap.h:740",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:get_swap_page"
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
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582530933,
      "name": "mem_cgroup_try_charge_swap",
      "external": false,
      "loc": "include/linux/swap.h:654",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:folio_alloc_swap"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583045422,
      "name": "mem_cgroup_try_charge_swap",
      "external": false,
      "loc": "include/linux/swap.h:664",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:folio_alloc_swap"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583254030,
      "name": "mem_cgroup_try_charge_swap",
      "external": false,
      "loc": "include/linux/swap.h:655",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:folio_alloc_swap"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583488520,
      "name": "mem_cgroup_try_charge_swap",
      "external": false,
      "loc": "include/linux/swap.h:646",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:folio_alloc_swap"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493216832,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7094",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493216832,
      "name": "mem_cgroup_try_charge_swap",
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226848048,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7094",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226848048,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286730240,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7094",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286730240,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272993104,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7094",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272993104,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581731600,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7094",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581731600,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581670304,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7094",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581670304,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581722912,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7094",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581722912,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```

```json
{
  "name": "mem_cgroup_try_charge_swap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581791120,
      "name": "mem_cgroup_try_charge_swap",
      "external": true,
      "loc": "mm/memcontrol.c:7094",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap_slots.c:get_swap_page",
        "mm/swap_slots.c:get_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791120,
      "name": "mem_cgroup_try_charge_swap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
```
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int mem_cgroup_try_charge_swap(struct page * page, swp_entry_t entry)
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
