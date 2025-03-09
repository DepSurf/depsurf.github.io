# Function: <code>mem_cgroup_try_charge_delay</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576336,
      "name": "mem_cgroup_try_charge_delay",
      "external": true,
      "loc": "mm/memcontrol.c:5921",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576336,
      "name": "mem_cgroup_try_charge_delay",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581687600,
      "name": "mem_cgroup_try_charge_delay",
      "external": true,
      "loc": "mm/memcontrol.c:6213",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687600,
      "name": "mem_cgroup_try_charge_delay",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581761056,
      "name": "mem_cgroup_try_charge_delay",
      "external": true,
      "loc": "mm/memcontrol.c:6553",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761056,
      "name": "mem_cgroup_try_charge_delay",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493214960,
      "name": "mem_cgroup_try_charge_delay",
      "external": true,
      "loc": "mm/memcontrol.c:6553",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493214960,
      "name": "mem_cgroup_try_charge_delay",
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
int mem_cgroup_try_charge_delay(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226846068,
      "name": "mem_cgroup_try_charge_delay",
      "external": true,
      "loc": "mm/memcontrol.c:6553",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226846068,
      "name": "mem_cgroup_try_charge_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int mem_cgroup_try_charge_delay(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286727328,
      "name": "mem_cgroup_try_charge_delay",
      "external": true,
      "loc": "mm/memcontrol.c:6553",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286727328,
      "name": "mem_cgroup_try_charge_delay",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272991426,
      "name": "mem_cgroup_try_charge_delay",
      "external": true,
      "loc": "mm/memcontrol.c:6553",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272991426,
      "name": "mem_cgroup_try_charge_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int mem_cgroup_try_charge_delay(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581729792,
      "name": "mem_cgroup_try_charge_delay",
      "external": true,
      "loc": "mm/memcontrol.c:6553",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729792,
      "name": "mem_cgroup_try_charge_delay",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668560,
      "name": "mem_cgroup_try_charge_delay",
      "external": true,
      "loc": "mm/memcontrol.c:6553",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668560,
      "name": "mem_cgroup_try_charge_delay",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581721104,
      "name": "mem_cgroup_try_charge_delay",
      "external": true,
      "loc": "mm/memcontrol.c:6553",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721104,
      "name": "mem_cgroup_try_charge_delay",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int mem_cgroup_try_charge_delay(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581789184,
      "name": "mem_cgroup_try_charge_delay",
      "external": true,
      "loc": "mm/memcontrol.c:6553",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789184,
      "name": "mem_cgroup_try_charge_delay",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int mem_cgroup_try_charge_delay(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int mem_cgroup_try_charge_delay(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
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
