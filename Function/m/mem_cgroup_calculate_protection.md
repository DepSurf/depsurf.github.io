# Function: <code>mem_cgroup_calculate_protection</code>

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
void mem_cgroup_calculate_protection(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_calculate_protection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582030400,
      "name": "mem_cgroup_calculate_protection",
      "external": true,
      "loc": "mm/memcontrol.c:6646",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582030400,
      "name": "mem_cgroup_calculate_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void mem_cgroup_calculate_protection(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_calculate_protection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582056592,
      "name": "mem_cgroup_calculate_protection",
      "external": true,
      "loc": "mm/memcontrol.c:6475",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582056592,
      "name": "mem_cgroup_calculate_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
void mem_cgroup_calculate_protection(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_calculate_protection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582364640,
      "name": "mem_cgroup_calculate_protection",
      "external": true,
      "loc": "mm/memcontrol.c:6661",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582364640,
      "name": "mem_cgroup_calculate_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
void mem_cgroup_calculate_protection(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_calculate_protection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582862112,
      "name": "mem_cgroup_calculate_protection",
      "external": true,
      "loc": "mm/memcontrol.c:6667",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582862112,
      "name": "mem_cgroup_calculate_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
void mem_cgroup_calculate_protection(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_calculate_protection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583409552,
      "name": "mem_cgroup_calculate_protection",
      "external": true,
      "loc": "mm/memcontrol.c:6857",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:lru_gen_age_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583409552,
      "name": "mem_cgroup_calculate_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
void mem_cgroup_calculate_protection(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_calculate_protection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583629808,
      "name": "mem_cgroup_calculate_protection",
      "external": true,
      "loc": "mm/memcontrol.c:6925",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_one",
        "mm/vmscan.c:lru_gen_age_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629808,
      "name": "mem_cgroup_calculate_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
void mem_cgroup_calculate_protection(struct mem_cgroup * root, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_calculate_protection",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583824384,
      "name": "mem_cgroup_calculate_protection",
      "external": true,
      "loc": "mm/memcontrol.c:7224",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_one",
        "mm/vmscan.c:lru_gen_age_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583824384,
      "name": "mem_cgroup_calculate_protection",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
void mem_cgroup_calculate_protection(struct mem_cgroup * root, struct mem_cgroup * memcg)
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
