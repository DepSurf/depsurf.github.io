# Function: <code>try_charge_memcg</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int try_charge_memcg(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge_memcg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582352176,
      "name": "try_charge_memcg",
      "external": false,
      "loc": "mm/memcontrol.c:2579",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:obj_cgroup_charge_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582352176,
      "name": "try_charge_memcg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1856
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
int try_charge_memcg(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge_memcg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582851568,
      "name": "try_charge_memcg",
      "external": false,
      "loc": "mm/memcontrol.c:2570",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582851568,
      "name": "try_charge_memcg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1847
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
int try_charge_memcg(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge_memcg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583398192,
      "name": "try_charge_memcg",
      "external": false,
      "loc": "mm/memcontrol.c:2631",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583398192,
      "name": "try_charge_memcg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1970
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
int try_charge_memcg(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge_memcg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583618656,
      "name": "try_charge_memcg",
      "external": false,
      "loc": "mm/memcontrol.c:2641",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583618656,
      "name": "try_charge_memcg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1990
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
int try_charge_memcg(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```

```json
{
  "name": "try_charge_memcg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583813600,
      "name": "try_charge_memcg",
      "external": false,
      "loc": "mm/memcontrol.c:2728",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:mem_cgroup_hugetlb_try_charge",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583813600,
      "name": "try_charge_memcg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1992
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int try_charge_memcg(struct mem_cgroup * memcg, gfp_t gfp_mask, unsigned int nr_pages)
```
</details>
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
