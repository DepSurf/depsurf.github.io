# Function: <code>bpf_map_uncharge_memlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580363137,
      "name": "bpf_map_uncharge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:67",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
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
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580420001,
      "name": "bpf_map_uncharge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:82",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
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
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580474659,
      "name": "bpf_map_uncharge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:110",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
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
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580498407,
      "name": "bpf_map_uncharge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:121",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
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
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580553665,
      "name": "bpf_map_uncharge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:168",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
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
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580636290,
      "name": "bpf_map_uncharge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:202",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
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
void bpf_map_uncharge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580693152,
      "name": "bpf_map_uncharge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:232",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693152,
      "name": "bpf_map_uncharge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void bpf_map_uncharge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580762096,
      "name": "bpf_map_uncharge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:248",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580762096,
      "name": "bpf_map_uncharge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void bpf_map_uncharge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580812160,
      "name": "bpf_map_uncharge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:251",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580812160,
      "name": "bpf_map_uncharge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void bpf_map_uncharge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936384,
      "name": "bpf_map_uncharge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:405",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936384,
      "name": "bpf_map_uncharge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void bpf_map_uncharge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492132768,
      "name": "bpf_map_uncharge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:251",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492132768,
      "name": "bpf_map_uncharge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void bpf_map_uncharge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226031320,
      "name": "bpf_map_uncharge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:251",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226031320,
      "name": "bpf_map_uncharge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void bpf_map_uncharge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285339856,
      "name": "bpf_map_uncharge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:251",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285339856,
      "name": "bpf_map_uncharge_memlock",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void bpf_map_uncharge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272298702,
      "name": "bpf_map_uncharge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:251",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272298702,
      "name": "bpf_map_uncharge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void bpf_map_uncharge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580780960,
      "name": "bpf_map_uncharge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:251",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780960,
      "name": "bpf_map_uncharge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void bpf_map_uncharge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580727136,
      "name": "bpf_map_uncharge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:251",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727136,
      "name": "bpf_map_uncharge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void bpf_map_uncharge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772208,
      "name": "bpf_map_uncharge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:251",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772208,
      "name": "bpf_map_uncharge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void bpf_map_uncharge_memlock(struct bpf_map * map, u32 pages)
```

```json
{
  "name": "bpf_map_uncharge_memlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580830432,
      "name": "bpf_map_uncharge_memlock",
      "external": true,
      "loc": "kernel/bpf/syscall.c:251",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830432,
      "name": "bpf_map_uncharge_memlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void bpf_map_uncharge_memlock(struct bpf_map * map, u32 pages)
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
void bpf_map_uncharge_memlock(struct bpf_map * map, u32 pages)
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
