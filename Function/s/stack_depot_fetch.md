# Function: <code>stack_depot_fetch</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int stack_depot_fetch(depot_stack_handle_t handle, long unsigned int * * entries)
```

```json
{
  "name": "stack_depot_fetch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586642512,
      "name": "stack_depot_fetch",
      "external": true,
      "loc": "lib/stackdepot.c:314",
      "file": "lib/stackdepot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/stackdepot.c:stack_depot_print",
        "lib/stackdepot.c:stack_depot_snprint"
      ],
      "caller_func": [
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:__kmem_obj_info",
        "mm/slub.c:__kmem_obj_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586640816,
      "name": "stack_depot_fetch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int stack_depot_fetch(depot_stack_handle_t handle, long unsigned int * * entries)
```

```json
{
  "name": "stack_depot_fetch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587886496,
      "name": "stack_depot_fetch",
      "external": true,
      "loc": "lib/stackdepot.c:364",
      "file": "lib/stackdepot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/stackdepot.c:stack_depot_print",
        "lib/stackdepot.c:stack_depot_snprint"
      ],
      "caller_func": [
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:__kmem_obj_info",
        "mm/slub.c:__kmem_obj_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884528,
      "name": "stack_depot_fetch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int stack_depot_fetch(depot_stack_handle_t handle, long unsigned int * * entries)
```

```json
{
  "name": "stack_depot_fetch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588158512,
      "name": "stack_depot_fetch",
      "external": true,
      "loc": "lib/stackdepot.c:460",
      "file": "lib/stackdepot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/stackdepot.c:stack_depot_snprint",
        "lib/stackdepot.c:stack_depot_print"
      ],
      "caller_func": [
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:__kmem_obj_info",
        "mm/slub.c:__kmem_obj_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588156096,
      "name": "stack_depot_fetch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int stack_depot_fetch(depot_stack_handle_t handle, long unsigned int * * entries)
```

```json
{
  "name": "stack_depot_fetch",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588448000,
      "name": "stack_depot_fetch",
      "external": true,
      "loc": "lib/stackdepot.c:731",
      "file": "lib/stackdepot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/stackdepot.c:stack_depot_snprint",
        "lib/stackdepot.c:stack_depot_print"
      ],
      "caller_func": [
        "mm/slub.c:slab_debugfs_show",
        "mm/slub.c:__kmem_obj_info",
        "mm/slub.c:__kmem_obj_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597634739,
      "name": "stack_depot_fetch.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588446432,
      "name": "stack_depot_fetch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
unsigned int stack_depot_fetch(depot_stack_handle_t handle, long unsigned int * * entries)
```
</details>
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
