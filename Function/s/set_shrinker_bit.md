# Function: <code>set_shrinker_bit</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581427056,
      "name": "set_shrinker_bit",
      "external": true,
      "loc": "mm/vmscan.c:332",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:list_lru_add",
        "mm/huge_memory.c:deferred_split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581427056,
      "name": "set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581678992,
      "name": "set_shrinker_bit",
      "external": true,
      "loc": "mm/vmscan.c:336",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/list_lru.c:memcg_drain_all_list_lrus",
        "mm/list_lru.c:list_lru_add",
        "mm/huge_memory.c:deferred_split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678992,
      "name": "set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582055696,
      "name": "set_shrinker_bit",
      "external": true,
      "loc": "mm/vmscan.c:338",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:list_lru_add",
        "mm/huge_memory.c:deferred_split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582055696,
      "name": "set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582528288,
      "name": "set_shrinker_bit",
      "external": true,
      "loc": "mm/vmscan.c:352",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:list_lru_add",
        "mm/huge_memory.c:deferred_split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582528288,
      "name": "set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582731088,
      "name": "set_shrinker_bit",
      "external": true,
      "loc": "mm/vmscan.c:335",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:list_lru_add",
        "mm/huge_memory.c:deferred_split_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582731088,
      "name": "set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
```

```json
{
  "name": "set_shrinker_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582926896,
      "name": "set_shrinker_bit",
      "external": true,
      "loc": "mm/shrinker.c:194",
      "file": "mm/shrinker.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shrinker.c:shrink_slab_memcg",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:list_lru_putback",
        "mm/list_lru.c:list_lru_add",
        "mm/huge_memory.c:deferred_split_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582926896,
      "name": "set_shrinker_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void set_shrinker_bit(struct mem_cgroup * memcg, int nid, int shrinker_id)
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
