# Function: <code>bpf_cgroup_storage_calculate_size</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map * map, u32 * pages)
```

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580779200,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:440",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580779200,
      "name": "bpf_cgroup_storage_calculate_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map * map, u32 * pages)
```

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580863856,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:460",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580863856,
      "name": "bpf_cgroup_storage_calculate_size",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map * map, u32 * pages)
```

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580914880,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:460",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914880,
      "name": "bpf_cgroup_storage_calculate_size",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map * map, u32 * pages)
```

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581060896,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:460",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581060896,
      "name": "bpf_cgroup_storage_calculate_size",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581074658,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:469",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581089650,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:470",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581318771,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:476",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581620643,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:476",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
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
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582005563,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:475",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
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
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582196587,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:482",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
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
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582345499,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:482",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map * map, u32 * pages)
```

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492246816,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:460",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492246816,
      "name": "bpf_cgroup_storage_calculate_size",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map * map, u32 * pages)
```

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226140984,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:460",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226140984,
      "name": "bpf_cgroup_storage_calculate_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map * map, u32 * pages)
```

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285476640,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:460",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285476640,
      "name": "bpf_cgroup_storage_calculate_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map * map, u32 * pages)
```

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272391000,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:460",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272391000,
      "name": "bpf_cgroup_storage_calculate_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map * map, u32 * pages)
```

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580883680,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:460",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580883680,
      "name": "bpf_cgroup_storage_calculate_size",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map * map, u32 * pages)
```

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580829744,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:460",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580829744,
      "name": "bpf_cgroup_storage_calculate_size",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map * map, u32 * pages)
```

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580874928,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:460",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580874928,
      "name": "bpf_cgroup_storage_calculate_size",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map * map, u32 * pages)
```

```json
{
  "name": "bpf_cgroup_storage_calculate_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580933520,
      "name": "bpf_cgroup_storage_calculate_size",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:460",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_free",
        "kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933520,
      "name": "bpf_cgroup_storage_calculate_size",
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map * map, u32 * pages)
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
size_t bpf_cgroup_storage_calculate_size(struct bpf_map * map, u32 * pages)
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
