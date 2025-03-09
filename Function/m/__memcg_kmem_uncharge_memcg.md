# Function: <code>__memcg_kmem_uncharge_memcg</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __memcg_kmem_uncharge_memcg(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "__memcg_kmem_uncharge_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581685472,
      "name": "__memcg_kmem_uncharge_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:2863",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__free_slab",
        "mm/memcontrol.c:__memcg_kmem_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581685472,
      "name": "__memcg_kmem_uncharge_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void __memcg_kmem_uncharge_memcg(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "__memcg_kmem_uncharge_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758352,
      "name": "__memcg_kmem_uncharge_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3072",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__free_slab",
        "mm/memcontrol.c:__memcg_kmem_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758352,
      "name": "__memcg_kmem_uncharge_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void __memcg_kmem_uncharge_memcg(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "__memcg_kmem_uncharge_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493212056,
      "name": "__memcg_kmem_uncharge_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3072",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__free_slab",
        "mm/memcontrol.c:__memcg_kmem_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493212056,
      "name": "__memcg_kmem_uncharge_memcg",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __memcg_kmem_uncharge_memcg(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "__memcg_kmem_uncharge_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226842736,
      "name": "__memcg_kmem_uncharge_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3072",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__free_slab",
        "mm/memcontrol.c:__memcg_kmem_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226842736,
      "name": "__memcg_kmem_uncharge_memcg",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __memcg_kmem_uncharge_memcg(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "__memcg_kmem_uncharge_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286722656,
      "name": "__memcg_kmem_uncharge_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3072",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__free_slab",
        "mm/memcontrol.c:__memcg_kmem_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286722656,
      "name": "__memcg_kmem_uncharge_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void __memcg_kmem_uncharge_memcg(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "__memcg_kmem_uncharge_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272988710,
      "name": "__memcg_kmem_uncharge_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3072",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__free_slab",
        "mm/memcontrol.c:__memcg_kmem_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272988710,
      "name": "__memcg_kmem_uncharge_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void __memcg_kmem_uncharge_memcg(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "__memcg_kmem_uncharge_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581727088,
      "name": "__memcg_kmem_uncharge_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3072",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__free_slab",
        "mm/memcontrol.c:__memcg_kmem_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581727088,
      "name": "__memcg_kmem_uncharge_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void __memcg_kmem_uncharge_memcg(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "__memcg_kmem_uncharge_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581665872,
      "name": "__memcg_kmem_uncharge_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3072",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__free_slab",
        "mm/memcontrol.c:__memcg_kmem_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581665872,
      "name": "__memcg_kmem_uncharge_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void __memcg_kmem_uncharge_memcg(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "__memcg_kmem_uncharge_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718400,
      "name": "__memcg_kmem_uncharge_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3072",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__free_slab",
        "mm/memcontrol.c:__memcg_kmem_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718400,
      "name": "__memcg_kmem_uncharge_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void __memcg_kmem_uncharge_memcg(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "__memcg_kmem_uncharge_memcg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581786288,
      "name": "__memcg_kmem_uncharge_memcg",
      "external": true,
      "loc": "mm/memcontrol.c:3072",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__free_slab",
        "mm/memcontrol.c:__memcg_kmem_uncharge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786288,
      "name": "__memcg_kmem_uncharge_memcg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void __memcg_kmem_uncharge_memcg(struct mem_cgroup * memcg, unsigned int nr_pages)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __memcg_kmem_uncharge_memcg(struct mem_cgroup * memcg, unsigned int nr_pages)
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
