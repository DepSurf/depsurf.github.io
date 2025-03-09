# Function: <code>bpf_jit_uncharge_modmem</code>

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
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580682865,
      "name": "bpf_jit_uncharge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:738",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
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
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580751281,
      "name": "bpf_jit_uncharge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:780",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
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
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580801841,
      "name": "bpf_jit_uncharge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:780",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
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
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580919508,
      "name": "bpf_jit_uncharge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:836",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_jit_uncharge_modmem(u32 pages)
```

```json
{
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580915636,
      "name": "bpf_jit_uncharge_modmem",
      "external": true,
      "loc": "kernel/bpf/core.c:833",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_tramp_image_alloc",
        "kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915216,
      "name": "bpf_jit_uncharge_modmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_jit_uncharge_modmem(u32 pages)
```

```json
{
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580919383,
      "name": "bpf_jit_uncharge_modmem",
      "external": true,
      "loc": "kernel/bpf/core.c:839",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918960,
      "name": "bpf_jit_uncharge_modmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_jit_uncharge_modmem(u32 pages)
```

```json
{
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581121895,
      "name": "bpf_jit_uncharge_modmem",
      "external": true,
      "loc": "kernel/bpf/core.c:841",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121472,
      "name": "bpf_jit_uncharge_modmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void bpf_jit_uncharge_modmem(u32 size)
```

```json
{
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581391073,
      "name": "bpf_jit_uncharge_modmem",
      "external": true,
      "loc": "kernel/bpf/core.c:1018",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390560,
      "name": "bpf_jit_uncharge_modmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void bpf_jit_uncharge_modmem(u32 size)
```

```json
{
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581740289,
      "name": "bpf_jit_uncharge_modmem",
      "external": true,
      "loc": "kernel/bpf/core.c:992",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581739696,
      "name": "bpf_jit_uncharge_modmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void bpf_jit_uncharge_modmem(u32 size)
```

```json
{
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581899761,
      "name": "bpf_jit_uncharge_modmem",
      "external": true,
      "loc": "kernel/bpf/core.c:993",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899168,
      "name": "bpf_jit_uncharge_modmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void bpf_jit_uncharge_modmem(u32 size)
```

```json
{
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582024001,
      "name": "bpf_jit_uncharge_modmem",
      "external": true,
      "loc": "kernel/bpf/core.c:1036",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc",
        "kernel/bpf/bpf_struct_ops.c:__bpf_struct_ops_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582022640,
      "name": "bpf_jit_uncharge_modmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492116452,
      "name": "bpf_jit_uncharge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:780",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
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
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226017720,
      "name": "bpf_jit_uncharge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:780",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
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
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285323968,
      "name": "bpf_jit_uncharge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:780",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
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
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272288946,
      "name": "bpf_jit_uncharge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:780",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_free",
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
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580770641,
      "name": "bpf_jit_uncharge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:780",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
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
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580716817,
      "name": "bpf_jit_uncharge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:780",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
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
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580761889,
      "name": "bpf_jit_uncharge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:780",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
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
  "name": "bpf_jit_uncharge_modmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580820033,
      "name": "bpf_jit_uncharge_modmem",
      "external": false,
      "loc": "kernel/bpf/core.c:780",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
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
void bpf_jit_uncharge_modmem(u32 pages)
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
