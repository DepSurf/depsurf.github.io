# Function: <code>map_iter_alloc</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580681700,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:176",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580752452,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:176",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580835190,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:173",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580886214,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:174",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
struct map_iter * map_iter_alloc(struct bpf_map * map)
```

```json
{
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581024480,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:195",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpffs_map_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581024480,
      "name": "map_iter_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
struct map_iter * map_iter_alloc(struct bpf_map * map)
```

```json
{
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581030688,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:196",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpffs_map_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030688,
      "name": "map_iter_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
struct map_iter * map_iter_alloc(struct bpf_map * map)
```

```json
{
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581041936,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:197",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpffs_map_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581041936,
      "name": "map_iter_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
struct map_iter * map_iter_alloc(struct bpf_map * map)
```

```json
{
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581264704,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:197",
      "file": "kernel/bpf/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpffs_map_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264704,
      "name": "map_iter_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581555926,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:197",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581928214,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:197",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582111398,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:197",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582251546,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:194",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492211540,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:174",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226108972,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:174",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285432468,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:174",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272360274,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:174",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580855014,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:174",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580801190,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:174",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580846262,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:174",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
  "name": "map_iter_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580904550,
      "name": "map_iter_alloc",
      "external": false,
      "loc": "kernel/bpf/inode.c:174",
      "file": "kernel/bpf/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/inode.c:bpffs_map_open"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct map_iter * map_iter_alloc(struct bpf_map * map)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct map_iter * map_iter_alloc(struct bpf_map * map)
```
</details>
</li>
</ul>
