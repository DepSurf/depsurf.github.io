# Function: <code>mod_objcg_state</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mod_objcg_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581887070,
      "name": "mod_objcg_state",
      "external": false,
      "loc": "mm/slab.h:288",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:memcg_slab_post_alloc_hook"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mod_objcg_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581917745,
      "name": "mod_objcg_state",
      "external": false,
      "loc": "mm/slab.h:286",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:memcg_slab_post_alloc_hook"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void mod_objcg_state(struct obj_cgroup * objcg, struct pglist_data * pgdat, enum node_stat_item idx, int nr)
```

```json
{
  "name": "mod_objcg_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582361344,
      "name": "mod_objcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:3074",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582361344,
      "name": "mod_objcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
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
void mod_objcg_state(struct obj_cgroup * objcg, struct pglist_data * pgdat, enum node_stat_item idx, int nr)
```

```json
{
  "name": "mod_objcg_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582858592,
      "name": "mod_objcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:3056",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582858592,
      "name": "mod_objcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 701
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
void mod_objcg_state(struct obj_cgroup * objcg, struct pglist_data * pgdat, enum node_stat_item idx, int nr)
```

```json
{
  "name": "mod_objcg_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583405840,
      "name": "mod_objcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:3156",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:__kmem_cache_free",
        "mm/slub.c:memcg_slab_free_hook",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583405840,
      "name": "mod_objcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 701
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
void mod_objcg_state(struct obj_cgroup * objcg, struct pglist_data * pgdat, enum node_stat_item idx, int nr)
```

```json
{
  "name": "mod_objcg_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583626144,
      "name": "mod_objcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:3166",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:__kmem_cache_free",
        "mm/slub.c:memcg_slab_free_hook",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583626144,
      "name": "mod_objcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
void mod_objcg_state(struct obj_cgroup * objcg, struct pglist_data * pgdat, enum node_stat_item idx, int nr)
```

```json
{
  "name": "mod_objcg_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583820768,
      "name": "mod_objcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:3358",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__memcg_slab_free_hook",
        "mm/slub.c:__memcg_slab_post_alloc_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583820768,
      "name": "mod_objcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
void mod_objcg_state(struct obj_cgroup * objcg, struct pglist_data * pgdat, enum node_stat_item idx, int nr)
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
