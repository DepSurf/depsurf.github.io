# Function: <code>__cpu_map_entry_alloc</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_entry_alloc(u32 qsize, u32 cpu, int map_id)
```

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580614400,
      "name": "__cpu_map_entry_alloc",
      "external": true,
      "loc": "kernel/bpf/cpumap.c:340",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580614400,
      "name": "__cpu_map_entry_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580722966,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:302",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580803144,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:302",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580890886,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:334",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580943526,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:334",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_entry_alloc(u32 qsize, u32 cpu, int map_id)
```

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105888,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:310",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105888,
      "name": "__cpu_map_entry_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
struct bpf_cpu_map_entry * __cpu_map_entry_alloc(struct bpf_map * map, struct bpf_cpumap_val * value, u32 cpu)
```

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581132560,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:401",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132560,
      "name": "__cpu_map_entry_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 603
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
struct bpf_cpu_map_entry * __cpu_map_entry_alloc(struct bpf_map * map, struct bpf_cpumap_val * value, u32 cpu)
```

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152752,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:359",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152752,
      "name": "__cpu_map_entry_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
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
struct bpf_cpu_map_entry * __cpu_map_entry_alloc(struct bpf_map * map, struct bpf_cpumap_val * value, u32 cpu)
```

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581389392,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:420",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581389392,
      "name": "__cpu_map_entry_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
struct bpf_cpu_map_entry * __cpu_map_entry_alloc(struct bpf_map * map, struct bpf_cpumap_val * value, u32 cpu)
```

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581713296,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:423",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581713296,
      "name": "__cpu_map_entry_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 727
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
struct bpf_cpu_map_entry * __cpu_map_entry_alloc(struct bpf_map * map, struct bpf_cpumap_val * value, u32 cpu)
```

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582120080,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:422",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120080,
      "name": "__cpu_map_entry_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 750
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
struct bpf_cpu_map_entry * __cpu_map_entry_alloc(struct bpf_map * map, struct bpf_cpumap_val * value, u32 cpu)
```

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582316688,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:426",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582316688,
      "name": "__cpu_map_entry_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 783
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
struct bpf_cpu_map_entry * __cpu_map_entry_alloc(struct bpf_map * map, struct bpf_cpumap_val * value, u32 cpu)
```

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582477728,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:386",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582477728,
      "name": "__cpu_map_entry_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 772
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492287900,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:334",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226172720,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:334",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285521524,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:334",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272419090,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:334",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580912326,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:334",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580858390,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:334",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580903574,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:334",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cpu_map_entry_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580964038,
      "name": "__cpu_map_entry_alloc",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:334",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_entry_alloc(u32 qsize, u32 cpu, int map_id)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_entry_alloc(u32 qsize, u32 cpu, int map_id)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct bpf_cpu_map_entry * __cpu_map_entry_alloc(u32 qsize, u32 cpu, int map_id)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_map * map</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_cpumap_val * value</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 qsize</code>
</li>
<li>
<b>Param removed. </b>
<code>int map_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>qsize, cpu, map_id</code> ➡️ <code>map, value, cpu</code>
</li>
</ul>
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
