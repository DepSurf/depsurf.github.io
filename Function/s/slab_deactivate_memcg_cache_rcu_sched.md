# Function: <code>slab_deactivate_memcg_cache_rcu_sched</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void slab_deactivate_memcg_cache_rcu_sched(struct kmem_cache * s, void (*)(struct kmem_cache *) deact_fn)
```

```json
{
  "name": "slab_deactivate_memcg_cache_rcu_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580841888,
      "name": "slab_deactivate_memcg_cache_rcu_sched",
      "external": true,
      "loc": "mm/slab_common.c:678",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmemcg_cache_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841888,
      "name": "slab_deactivate_memcg_cache_rcu_sched",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void slab_deactivate_memcg_cache_rcu_sched(struct kmem_cache * s, void (*)(struct kmem_cache *) deact_fn)
```

```json
{
  "name": "slab_deactivate_memcg_cache_rcu_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932576,
      "name": "slab_deactivate_memcg_cache_rcu_sched",
      "external": true,
      "loc": "mm/slab_common.c:687",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmemcg_cache_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932576,
      "name": "slab_deactivate_memcg_cache_rcu_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void slab_deactivate_memcg_cache_rcu_sched(struct kmem_cache * s, void (*)(struct kmem_cache *) deact_fn)
```

```json
{
  "name": "slab_deactivate_memcg_cache_rcu_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068560,
      "name": "slab_deactivate_memcg_cache_rcu_sched",
      "external": true,
      "loc": "mm/slab_common.c:713",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmemcg_cache_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068560,
      "name": "slab_deactivate_memcg_cache_rcu_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void slab_deactivate_memcg_cache_rcu_sched(struct kmem_cache * s, void (*)(struct kmem_cache *) deact_fn)
```

```json
{
  "name": "slab_deactivate_memcg_cache_rcu_sched",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581146352,
      "name": "slab_deactivate_memcg_cache_rcu_sched",
      "external": true,
      "loc": "mm/slab_common.c:740",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmemcg_cache_deactivate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581146352,
      "name": "slab_deactivate_memcg_cache_rcu_sched",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void slab_deactivate_memcg_cache_rcu_sched(struct kmem_cache * s, void (*)(struct kmem_cache *) deact_fn)
```
</details>
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void slab_deactivate_memcg_cache_rcu_sched(struct kmem_cache * s, void (*)(struct kmem_cache *) deact_fn)
```
</details>
</li>
</ul>
