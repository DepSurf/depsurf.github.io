# Function: <code>obj_cgroup_uncharge_pages</code>

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
void obj_cgroup_uncharge_pages(struct obj_cgroup * objcg, unsigned int nr_pages)
```

```json
{
  "name": "obj_cgroup_uncharge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582036896,
      "name": "obj_cgroup_uncharge_pages",
      "external": false,
      "loc": "mm/memcontrol.c:2905",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:obj_cgroup_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036896,
      "name": "obj_cgroup_uncharge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
void obj_cgroup_uncharge_pages(struct obj_cgroup * objcg, unsigned int nr_pages)
```

```json
{
  "name": "obj_cgroup_uncharge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582342784,
      "name": "obj_cgroup_uncharge_pages",
      "external": false,
      "loc": "mm/memcontrol.c:2973",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:obj_cgroup_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582342784,
      "name": "obj_cgroup_uncharge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
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
void obj_cgroup_uncharge_pages(struct obj_cgroup * objcg, unsigned int nr_pages)
```

```json
{
  "name": "obj_cgroup_uncharge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582839120,
      "name": "obj_cgroup_uncharge_pages",
      "external": false,
      "loc": "mm/memcontrol.c:2970",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:obj_cgroup_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582839120,
      "name": "obj_cgroup_uncharge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void obj_cgroup_uncharge_pages(struct obj_cgroup * objcg, unsigned int nr_pages)
```

```json
{
  "name": "obj_cgroup_uncharge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583384496,
      "name": "obj_cgroup_uncharge_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3070",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:obj_cgroup_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583384496,
      "name": "obj_cgroup_uncharge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void obj_cgroup_uncharge_pages(struct obj_cgroup * objcg, unsigned int nr_pages)
```

```json
{
  "name": "obj_cgroup_uncharge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583605120,
      "name": "obj_cgroup_uncharge_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3080",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:obj_cgroup_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583605120,
      "name": "obj_cgroup_uncharge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void obj_cgroup_uncharge_pages(struct obj_cgroup * objcg, unsigned int nr_pages)
```

```json
{
  "name": "obj_cgroup_uncharge_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583799728,
      "name": "obj_cgroup_uncharge_pages",
      "external": false,
      "loc": "mm/memcontrol.c:3272",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:obj_cgroup_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583799728,
      "name": "obj_cgroup_uncharge_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void obj_cgroup_uncharge_pages(struct obj_cgroup * objcg, unsigned int nr_pages)
```
</details>
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
