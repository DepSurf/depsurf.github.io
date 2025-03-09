# Function: <code>obj_cgroup_charge_pages</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int obj_cgroup_charge_pages(struct obj_cgroup * objcg, gfp_t gfp, unsigned int nr_pages)
```

```json
{
  "name": "obj_cgroup_charge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582049440,
      "name": "obj_cgroup_charge_pages",
      "external": false,
      "loc": "mm/memcontrol.c:2927",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582049440,
      "name": "obj_cgroup_charge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int obj_cgroup_charge_pages(struct obj_cgroup * objcg, gfp_t gfp, unsigned int nr_pages)
```

```json
{
  "name": "obj_cgroup_charge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582356336,
      "name": "obj_cgroup_charge_pages",
      "external": false,
      "loc": "mm/memcontrol.c:2995",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582356336,
      "name": "obj_cgroup_charge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "obj_cgroup_charge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582859362,
      "name": "obj_cgroup_charge_pages",
      "external": false,
      "loc": "mm/memcontrol.c:2991",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_page"
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
  "name": "obj_cgroup_charge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583406626,
      "name": "obj_cgroup_charge_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3091",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_page"
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
  "name": "obj_cgroup_charge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583626930,
      "name": "obj_cgroup_charge_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3101",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_page"
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
  "name": "obj_cgroup_charge_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583821554,
      "name": "obj_cgroup_charge_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3293",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:__memcg_kmem_charge_page"
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int obj_cgroup_charge_pages(struct obj_cgroup * objcg, gfp_t gfp, unsigned int nr_pages)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int obj_cgroup_charge_pages(struct obj_cgroup * objcg, gfp_t gfp, unsigned int nr_pages)
```
</details>
</li>
</ul>
