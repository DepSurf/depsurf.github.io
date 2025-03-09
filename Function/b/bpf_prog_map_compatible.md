# Function: <code>bpf_prog_map_compatible</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool bpf_prog_map_compatible(struct bpf_map * map, const struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_map_compatible",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581394745,
      "name": "bpf_prog_map_compatible",
      "external": true,
      "loc": "kernel/bpf/core.c:2117",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_select_runtime"
      ],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581383808,
      "name": "bpf_prog_map_compatible.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071593953741,
      "name": "bpf_prog_map_compatible.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071581392544,
      "name": "bpf_prog_map_compatible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool bpf_prog_map_compatible(struct bpf_map * map, const struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_map_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_map_compatible",
      "external": true,
      "loc": "kernel/bpf/core.c:2089",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596013395,
      "name": "bpf_prog_map_compatible.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071581741856,
      "name": "bpf_prog_map_compatible",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool bpf_prog_map_compatible(struct bpf_map * map, const struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_map_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_map_compatible",
      "external": true,
      "loc": "kernel/bpf/core.c:2098",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596533370,
      "name": "bpf_prog_map_compatible.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071581901136,
      "name": "bpf_prog_map_compatible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool bpf_prog_map_compatible(struct bpf_map * map, const struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_map_compatible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_map_compatible",
      "external": true,
      "loc": "kernel/bpf/core.c:2274",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_select_runtime",
        "kernel/bpf/arraymap.c:prog_fd_array_get_ptr",
        "kernel/bpf/devmap.c:__dev_map_alloc_node",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597434112,
      "name": "bpf_prog_map_compatible.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071582024800,
      "name": "bpf_prog_map_compatible",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool bpf_prog_map_compatible(struct bpf_map * map, const struct bpf_prog * fp)
```
</details>
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
