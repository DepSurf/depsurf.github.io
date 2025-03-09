# Function: <code>bpf_jit_charge_modmem</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580682659,
      "name": "bpf_jit_charge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:725",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
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
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580751083,
      "name": "bpf_jit_charge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:767",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
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
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580801643,
      "name": "bpf_jit_charge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:767",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580919167,
      "name": "bpf_jit_charge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:823",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int bpf_jit_charge_modmem(u32 pages)
```

```json
{
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915136,
      "name": "bpf_jit_charge_modmem",
      "external": true,
      "loc": "kernel/bpf/core.c:820",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/trampoline.c:bpf_tramp_image_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915136,
      "name": "bpf_jit_charge_modmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int bpf_jit_charge_modmem(u32 pages)
```

```json
{
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580918880,
      "name": "bpf_jit_charge_modmem",
      "external": true,
      "loc": "kernel/bpf/core.c:826",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918880,
      "name": "bpf_jit_charge_modmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int bpf_jit_charge_modmem(u32 pages)
```

```json
{
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581121376,
      "name": "bpf_jit_charge_modmem",
      "external": true,
      "loc": "kernel/bpf/core.c:828",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121376,
      "name": "bpf_jit_charge_modmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int bpf_jit_charge_modmem(u32 size)
```

```json
{
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581390464,
      "name": "bpf_jit_charge_modmem",
      "external": true,
      "loc": "kernel/bpf/core.c:1006",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390464,
      "name": "bpf_jit_charge_modmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int bpf_jit_charge_modmem(u32 size)
```

```json
{
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581739568,
      "name": "bpf_jit_charge_modmem",
      "external": true,
      "loc": "kernel/bpf/core.c:980",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581739568,
      "name": "bpf_jit_charge_modmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int bpf_jit_charge_modmem(u32 size)
```

```json
{
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581899040,
      "name": "bpf_jit_charge_modmem",
      "external": true,
      "loc": "kernel/bpf/core.c:981",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899040,
      "name": "bpf_jit_charge_modmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int bpf_jit_charge_modmem(u32 size)
```

```json
{
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582022512,
      "name": "bpf_jit_charge_modmem",
      "external": true,
      "loc": "kernel/bpf/core.c:1024",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582022512,
      "name": "bpf_jit_charge_modmem",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492115980,
      "name": "bpf_jit_charge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:767",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
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
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226017456,
      "name": "bpf_jit_charge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:767",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
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
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285323436,
      "name": "bpf_jit_charge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:767",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
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
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272288624,
      "name": "bpf_jit_charge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:767",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
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
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580770443,
      "name": "bpf_jit_charge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:767",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
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
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580716619,
      "name": "bpf_jit_charge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:767",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
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
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580761691,
      "name": "bpf_jit_charge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:767",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
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
  "name": "bpf_jit_charge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580819835,
      "name": "bpf_jit_charge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:767",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int bpf_jit_charge_modmem(u32 pages)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 size</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 pages</code>
</li>
</ul>
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
