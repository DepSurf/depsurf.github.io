# Function: <code>memcg_flush_percpu_vmstats</code>

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
void memcg_flush_percpu_vmstats(struct mem_cgroup * memcg, bool slab_only)
```

```json
{
  "name": "memcg_flush_percpu_vmstats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581654224,
      "name": "memcg_flush_percpu_vmstats",
      "external": false,
      "loc": "mm/memcontrol.c:3261",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:__mem_cgroup_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581654224,
      "name": "memcg_flush_percpu_vmstats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
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
void memcg_flush_percpu_vmstats(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmstats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581726752,
      "name": "memcg_flush_percpu_vmstats",
      "external": false,
      "loc": "mm/memcontrol.c:3470",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581726752,
      "name": "memcg_flush_percpu_vmstats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
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
void memcg_flush_percpu_vmstats(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmstats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581944144,
      "name": "memcg_flush_percpu_vmstats",
      "external": false,
      "loc": "mm/memcontrol.c:3353",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581944144,
      "name": "memcg_flush_percpu_vmstats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
void memcg_flush_percpu_vmstats(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmstats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581991440,
      "name": "memcg_flush_percpu_vmstats",
      "external": false,
      "loc": "mm/memcontrol.c:3625",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991440,
      "name": "memcg_flush_percpu_vmstats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
void memcg_flush_percpu_vmstats(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmstats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493184952,
      "name": "memcg_flush_percpu_vmstats",
      "external": false,
      "loc": "mm/memcontrol.c:3470",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493184952,
      "name": "memcg_flush_percpu_vmstats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
void memcg_flush_percpu_vmstats(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmstats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226811568,
      "name": "memcg_flush_percpu_vmstats",
      "external": false,
      "loc": "mm/memcontrol.c:3470",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226811568,
      "name": "memcg_flush_percpu_vmstats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
void memcg_flush_percpu_vmstats(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmstats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286671744,
      "name": "memcg_flush_percpu_vmstats",
      "external": false,
      "loc": "mm/memcontrol.c:3470",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286671744,
      "name": "memcg_flush_percpu_vmstats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
void memcg_flush_percpu_vmstats(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmstats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272960840,
      "name": "memcg_flush_percpu_vmstats",
      "external": false,
      "loc": "mm/memcontrol.c:3470",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272960840,
      "name": "memcg_flush_percpu_vmstats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
void memcg_flush_percpu_vmstats(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmstats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581695488,
      "name": "memcg_flush_percpu_vmstats",
      "external": false,
      "loc": "mm/memcontrol.c:3470",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695488,
      "name": "memcg_flush_percpu_vmstats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
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
void memcg_flush_percpu_vmstats(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmstats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581634512,
      "name": "memcg_flush_percpu_vmstats",
      "external": false,
      "loc": "mm/memcontrol.c:3470",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634512,
      "name": "memcg_flush_percpu_vmstats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
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
void memcg_flush_percpu_vmstats(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmstats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581686800,
      "name": "memcg_flush_percpu_vmstats",
      "external": false,
      "loc": "mm/memcontrol.c:3470",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581686800,
      "name": "memcg_flush_percpu_vmstats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
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
void memcg_flush_percpu_vmstats(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmstats",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581753648,
      "name": "memcg_flush_percpu_vmstats",
      "external": false,
      "loc": "mm/memcontrol.c:3470",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581753648,
      "name": "memcg_flush_percpu_vmstats",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
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
void memcg_flush_percpu_vmstats(struct mem_cgroup * memcg, bool slab_only)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool slab_only</code>
</li>
</ul>
</details>
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
void memcg_flush_percpu_vmstats(struct mem_cgroup * memcg)
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
