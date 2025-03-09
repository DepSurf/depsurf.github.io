# Function: <code>memcg_exact_page_state</code>

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
long unsigned int memcg_exact_page_state(struct mem_cgroup * memcg, int idx)
```

```json
{
  "name": "memcg_exact_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581653664,
      "name": "memcg_exact_page_state",
      "external": false,
      "loc": "mm/memcontrol.c:4204",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653664,
      "name": "memcg_exact_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
long unsigned int memcg_exact_page_state(struct mem_cgroup * memcg, int idx)
```

```json
{
  "name": "memcg_exact_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581726192,
      "name": "memcg_exact_page_state",
      "external": false,
      "loc": "mm/memcontrol.c:4405",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581726192,
      "name": "memcg_exact_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_exact_page_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581979126,
      "name": "memcg_exact_page_state",
      "external": false,
      "loc": "mm/memcontrol.c:4285",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memcg_exact_page_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582029398,
      "name": "memcg_exact_page_state",
      "external": false,
      "loc": "mm/memcontrol.c:4550",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats"
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
long unsigned int memcg_exact_page_state(struct mem_cgroup * memcg, int idx)
```

```json
{
  "name": "memcg_exact_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493175592,
      "name": "memcg_exact_page_state",
      "external": false,
      "loc": "mm/memcontrol.c:4405",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493175592,
      "name": "memcg_exact_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
long unsigned int memcg_exact_page_state(struct mem_cgroup * memcg, int idx)
```

```json
{
  "name": "memcg_exact_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226812344,
      "name": "memcg_exact_page_state",
      "external": false,
      "loc": "mm/memcontrol.c:4405",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226812344,
      "name": "memcg_exact_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
long unsigned int memcg_exact_page_state(struct mem_cgroup * memcg, int idx)
```

```json
{
  "name": "memcg_exact_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286671536,
      "name": "memcg_exact_page_state",
      "external": false,
      "loc": "mm/memcontrol.c:4405",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286671536,
      "name": "memcg_exact_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
long unsigned int memcg_exact_page_state(struct mem_cgroup * memcg, int idx)
```

```json
{
  "name": "memcg_exact_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272961506,
      "name": "memcg_exact_page_state",
      "external": false,
      "loc": "mm/memcontrol.c:4405",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272961506,
      "name": "memcg_exact_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
long unsigned int memcg_exact_page_state(struct mem_cgroup * memcg, int idx)
```

```json
{
  "name": "memcg_exact_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581694928,
      "name": "memcg_exact_page_state",
      "external": false,
      "loc": "mm/memcontrol.c:4405",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694928,
      "name": "memcg_exact_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
long unsigned int memcg_exact_page_state(struct mem_cgroup * memcg, int idx)
```

```json
{
  "name": "memcg_exact_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581633952,
      "name": "memcg_exact_page_state",
      "external": false,
      "loc": "mm/memcontrol.c:4405",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581633952,
      "name": "memcg_exact_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
long unsigned int memcg_exact_page_state(struct mem_cgroup * memcg, int idx)
```

```json
{
  "name": "memcg_exact_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581686240,
      "name": "memcg_exact_page_state",
      "external": false,
      "loc": "mm/memcontrol.c:4405",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581686240,
      "name": "memcg_exact_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
long unsigned int memcg_exact_page_state(struct mem_cgroup * memcg, int idx)
```

```json
{
  "name": "memcg_exact_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581753088,
      "name": "memcg_exact_page_state",
      "external": false,
      "loc": "mm/memcontrol.c:4405",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_wb_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581753088,
      "name": "memcg_exact_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
long unsigned int memcg_exact_page_state(struct mem_cgroup * memcg, int idx)
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
long unsigned int memcg_exact_page_state(struct mem_cgroup * memcg, int idx)
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
