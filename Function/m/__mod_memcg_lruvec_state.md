# Function: <code>__mod_memcg_lruvec_state</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __mod_memcg_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_memcg_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015552,
      "name": "__mod_memcg_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:798",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:memcg_slab_post_alloc_hook",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015552,
      "name": "__mod_memcg_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
void __mod_memcg_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_memcg_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582041328,
      "name": "__mod_memcg_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:686",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:memcg_slab_post_alloc_hook",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041328,
      "name": "__mod_memcg_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void __mod_memcg_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_memcg_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582344304,
      "name": "__mod_memcg_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:721",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582344304,
      "name": "__mod_memcg_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void __mod_memcg_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_memcg_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582839520,
      "name": "__mod_memcg_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:695",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:mod_memcg_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582839520,
      "name": "__mod_memcg_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void __mod_memcg_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_memcg_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583384928,
      "name": "__mod_memcg_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:765",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:mod_memcg_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583384928,
      "name": "__mod_memcg_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void __mod_memcg_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_memcg_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583605552,
      "name": "__mod_memcg_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:790",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:mod_memcg_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583605552,
      "name": "__mod_memcg_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void __mod_memcg_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```

```json
{
  "name": "__mod_memcg_lruvec_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583800160,
      "name": "__mod_memcg_lruvec_state",
      "external": true,
      "loc": "mm/memcontrol.c:838",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:mod_memcg_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583800160,
      "name": "__mod_memcg_lruvec_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __mod_memcg_lruvec_state(struct lruvec * lruvec, enum node_stat_item idx, int val)
```
</details>
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
