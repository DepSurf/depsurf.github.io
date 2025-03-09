# Function: <code>bpf_prog_array_update_at</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_prog_array_update_at(struct bpf_prog_array * array, int index, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_array_update_at",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580917349,
      "name": "bpf_prog_array_update_at",
      "external": true,
      "loc": "kernel/bpf/core.c:1998",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_delete_safe_at"
      ],
      "caller_func": [
        "kernel/bpf/net_namespace.c:bpf_netns_link_update_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917424,
      "name": "bpf_prog_array_update_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_prog_array_update_at(struct bpf_prog_array * array, int index, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_array_update_at",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580921301,
      "name": "bpf_prog_array_update_at",
      "external": true,
      "loc": "kernel/bpf/core.c:2094",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_delete_safe_at"
      ],
      "caller_func": [
        "kernel/bpf/net_namespace.c:bpf_netns_link_update_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921376,
      "name": "bpf_prog_array_update_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_prog_array_update_at(struct bpf_prog_array * array, int index, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_array_update_at",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581123813,
      "name": "bpf_prog_array_update_at",
      "external": true,
      "loc": "kernel/bpf/core.c:2107",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_delete_safe_at"
      ],
      "caller_func": [
        "kernel/bpf/net_namespace.c:bpf_netns_link_update_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581123888,
      "name": "bpf_prog_array_update_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_prog_array_update_at(struct bpf_prog_array * array, int index, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_array_update_at",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581393205,
      "name": "bpf_prog_array_update_at",
      "external": true,
      "loc": "kernel/bpf/core.c:2393",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_delete_safe_at"
      ],
      "caller_func": [
        "kernel/bpf/net_namespace.c:bpf_netns_link_update_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393312,
      "name": "bpf_prog_array_update_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_prog_array_update_at(struct bpf_prog_array * array, int index, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_array_update_at",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581742949,
      "name": "bpf_prog_array_update_at",
      "external": true,
      "loc": "kernel/bpf/core.c:2387",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_delete_safe_at"
      ],
      "caller_func": [
        "kernel/bpf/net_namespace.c:bpf_netns_link_update_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581743072,
      "name": "bpf_prog_array_update_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_prog_array_update_at(struct bpf_prog_array * array, int index, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_array_update_at",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581902261,
      "name": "bpf_prog_array_update_at",
      "external": true,
      "loc": "kernel/bpf/core.c:2404",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_delete_safe_at"
      ],
      "caller_func": [
        "kernel/bpf/net_namespace.c:bpf_netns_link_update_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902384,
      "name": "bpf_prog_array_update_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_prog_array_update_at(struct bpf_prog_array * array, int index, struct bpf_prog * prog)
```

```json
{
  "name": "bpf_prog_array_update_at",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582025925,
      "name": "bpf_prog_array_update_at",
      "external": true,
      "loc": "kernel/bpf/core.c:2580",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_array_delete_safe_at"
      ],
      "caller_func": [
        "kernel/bpf/net_namespace.c:bpf_netns_link_update_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026048,
      "name": "bpf_prog_array_update_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int bpf_prog_array_update_at(struct bpf_prog_array * array, int index, struct bpf_prog * prog)
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
