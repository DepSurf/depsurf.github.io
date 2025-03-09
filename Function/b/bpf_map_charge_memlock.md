# Function: <code>bpf_map_charge_memlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580366971,
      "name": "bpf_map_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:49",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580424842,
      "name": "bpf_map_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:64",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580474545,
      "name": "bpf_map_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:92",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580494484,
      "name": "bpf_map_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:103",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580552532,
      "name": "bpf_map_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:150",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580635977,
      "name": "bpf_map_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:184",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int bpf_map_charge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580693104,
      "name": "bpf_map_charge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:221",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693104,
      "name": "bpf_map_charge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int bpf_map_charge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580762048,
      "name": "bpf_map_charge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:237",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580762048,
      "name": "bpf_map_charge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int bpf_map_charge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580812112,
      "name": "bpf_map_charge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:240",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580812112,
      "name": "bpf_map_charge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int bpf_map_charge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936304,
      "name": "bpf_map_charge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:394",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936304,
      "name": "bpf_map_charge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
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
int bpf_map_charge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492132696,
      "name": "bpf_map_charge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:240",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492132696,
      "name": "bpf_map_charge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int bpf_map_charge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226031264,
      "name": "bpf_map_charge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:240",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226031264,
      "name": "bpf_map_charge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int bpf_map_charge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285339728,
      "name": "bpf_map_charge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:240",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285339728,
      "name": "bpf_map_charge_memlock",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int bpf_map_charge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272298604,
      "name": "bpf_map_charge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:240",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272298604,
      "name": "bpf_map_charge_memlock",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int bpf_map_charge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580780912,
      "name": "bpf_map_charge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:240",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780912,
      "name": "bpf_map_charge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int bpf_map_charge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580727088,
      "name": "bpf_map_charge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:240",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727088,
      "name": "bpf_map_charge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int bpf_map_charge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772160,
      "name": "bpf_map_charge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:240",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772160,
      "name": "bpf_map_charge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int bpf_map_charge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_charge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580830384,
      "name": "bpf_map_charge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:240",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830384,
      "name": "bpf_map_charge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int bpf_map_charge_memlock(struct bpf_map * map, u32 pages)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int bpf_map_charge_memlock(struct bpf_map * map, u32 pages)
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
