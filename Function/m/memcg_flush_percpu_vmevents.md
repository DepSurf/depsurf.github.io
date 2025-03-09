# Function: <code>memcg_flush_percpu_vmevents</code>

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
void memcg_flush_percpu_vmevents(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581653408,
      "name": "memcg_flush_percpu_vmevents",
      "external": false,
      "loc": "mm/memcontrol.c:3308",
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
      "addr": 18446744071581653408,
      "name": "memcg_flush_percpu_vmevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void memcg_flush_percpu_vmevents(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725936,
      "name": "memcg_flush_percpu_vmevents",
      "external": false,
      "loc": "mm/memcontrol.c:3502",
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
      "addr": 18446744071581725936,
      "name": "memcg_flush_percpu_vmevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void memcg_flush_percpu_vmevents(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581943824,
      "name": "memcg_flush_percpu_vmevents",
      "external": false,
      "loc": "mm/memcontrol.c:3385",
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
      "addr": 18446744071581943824,
      "name": "memcg_flush_percpu_vmevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void memcg_flush_percpu_vmevents(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581991152,
      "name": "memcg_flush_percpu_vmevents",
      "external": false,
      "loc": "mm/memcontrol.c:3657",
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
      "addr": 18446744071581991152,
      "name": "memcg_flush_percpu_vmevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
void memcg_flush_percpu_vmevents(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493184112,
      "name": "memcg_flush_percpu_vmevents",
      "external": false,
      "loc": "mm/memcontrol.c:3502",
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
      "addr": 18446603336493184112,
      "name": "memcg_flush_percpu_vmevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void memcg_flush_percpu_vmevents(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226812056,
      "name": "memcg_flush_percpu_vmevents",
      "external": false,
      "loc": "mm/memcontrol.c:3502",
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
      "addr": 3226812056,
      "name": "memcg_flush_percpu_vmevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void memcg_flush_percpu_vmevents(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286671152,
      "name": "memcg_flush_percpu_vmevents",
      "external": false,
      "loc": "mm/memcontrol.c:3502",
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
      "addr": 13835058055286671152,
      "name": "memcg_flush_percpu_vmevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void memcg_flush_percpu_vmevents(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272961254,
      "name": "memcg_flush_percpu_vmevents",
      "external": false,
      "loc": "mm/memcontrol.c:3502",
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
      "addr": 18446743936272961254,
      "name": "memcg_flush_percpu_vmevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
void memcg_flush_percpu_vmevents(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581694672,
      "name": "memcg_flush_percpu_vmevents",
      "external": false,
      "loc": "mm/memcontrol.c:3502",
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
      "addr": 18446744071581694672,
      "name": "memcg_flush_percpu_vmevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void memcg_flush_percpu_vmevents(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581633696,
      "name": "memcg_flush_percpu_vmevents",
      "external": false,
      "loc": "mm/memcontrol.c:3502",
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
      "addr": 18446744071581633696,
      "name": "memcg_flush_percpu_vmevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void memcg_flush_percpu_vmevents(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581685984,
      "name": "memcg_flush_percpu_vmevents",
      "external": false,
      "loc": "mm/memcontrol.c:3502",
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
      "addr": 18446744071581685984,
      "name": "memcg_flush_percpu_vmevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void memcg_flush_percpu_vmevents(struct mem_cgroup * memcg)
```

```json
{
  "name": "memcg_flush_percpu_vmevents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581752832,
      "name": "memcg_flush_percpu_vmevents",
      "external": false,
      "loc": "mm/memcontrol.c:3502",
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
      "addr": 18446744071581752832,
      "name": "memcg_flush_percpu_vmevents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void memcg_flush_percpu_vmevents(struct mem_cgroup * memcg)
```
</details>
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
void memcg_flush_percpu_vmevents(struct mem_cgroup * memcg)
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
