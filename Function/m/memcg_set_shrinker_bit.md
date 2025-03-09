# Function: <code>memcg_set_shrinker_bit</code>

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
void memcg_set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "memcg_set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581557232,
      "name": "memcg_set_shrinker_bit",
      "external": true,
      "loc": "mm/memcontrol.c:426",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:list_lru_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581557232,
      "name": "memcg_set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void memcg_set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "memcg_set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581672752,
      "name": "memcg_set_shrinker_bit",
      "external": true,
      "loc": "mm/memcontrol.c:425",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:list_lru_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581672752,
      "name": "memcg_set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void memcg_set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "memcg_set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745008,
      "name": "memcg_set_shrinker_bit",
      "external": true,
      "loc": "mm/memcontrol.c:433",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:list_lru_add",
        "mm/huge_memory.c:deferred_split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745008,
      "name": "memcg_set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void memcg_set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "memcg_set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581966592,
      "name": "memcg_set_shrinker_bit",
      "external": true,
      "loc": "mm/memcontrol.c:424",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/list_lru.c:memcg_drain_list_lru_node",
        "mm/list_lru.c:list_lru_add",
        "mm/huge_memory.c:deferred_split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581966592,
      "name": "memcg_set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void memcg_set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "memcg_set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582015280,
      "name": "memcg_set_shrinker_bit",
      "external": true,
      "loc": "mm/memcontrol.c:510",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/list_lru.c:memcg_drain_list_lru_node",
        "mm/list_lru.c:list_lru_add",
        "mm/huge_memory.c:deferred_split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582015280,
      "name": "memcg_set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
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
void memcg_set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "memcg_set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493197792,
      "name": "memcg_set_shrinker_bit",
      "external": true,
      "loc": "mm/memcontrol.c:433",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:list_lru_add",
        "mm/huge_memory.c:deferred_split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493197792,
      "name": "memcg_set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void memcg_set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "memcg_set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226829300,
      "name": "memcg_set_shrinker_bit",
      "external": true,
      "loc": "mm/memcontrol.c:433",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:list_lru_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226829300,
      "name": "memcg_set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void memcg_set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "memcg_set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286701408,
      "name": "memcg_set_shrinker_bit",
      "external": true,
      "loc": "mm/memcontrol.c:433",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:list_lru_add",
        "mm/huge_memory.c:deferred_split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286701408,
      "name": "memcg_set_shrinker_bit",
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
void memcg_set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "memcg_set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272977246,
      "name": "memcg_set_shrinker_bit",
      "external": true,
      "loc": "mm/memcontrol.c:433",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:list_lru_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272977246,
      "name": "memcg_set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void memcg_set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "memcg_set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581713744,
      "name": "memcg_set_shrinker_bit",
      "external": true,
      "loc": "mm/memcontrol.c:433",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:list_lru_add",
        "mm/huge_memory.c:deferred_split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581713744,
      "name": "memcg_set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void memcg_set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "memcg_set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652656,
      "name": "memcg_set_shrinker_bit",
      "external": true,
      "loc": "mm/memcontrol.c:433",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:list_lru_add",
        "mm/huge_memory.c:deferred_split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652656,
      "name": "memcg_set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void memcg_set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "memcg_set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581705056,
      "name": "memcg_set_shrinker_bit",
      "external": true,
      "loc": "mm/memcontrol.c:433",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:list_lru_add",
        "mm/huge_memory.c:deferred_split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581705056,
      "name": "memcg_set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void memcg_set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "memcg_set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581772320,
      "name": "memcg_set_shrinker_bit",
      "external": true,
      "loc": "mm/memcontrol.c:433",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:list_lru_add",
        "mm/huge_memory.c:deferred_split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772320,
      "name": "memcg_set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void memcg_set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void memcg_set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
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
