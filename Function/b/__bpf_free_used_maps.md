# Function: <code>__bpf_free_used_maps</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void __bpf_free_used_maps(struct bpf_prog_aux * aux, struct bpf_map * * used_maps, u32 len)
```

```json
{
  "name": "__bpf_free_used_maps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580921408,
      "name": "__bpf_free_used_maps",
      "external": true,
      "loc": "kernel/bpf/core.c:2056",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921408,
      "name": "__bpf_free_used_maps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_free_used_maps(struct bpf_prog_aux * aux, struct bpf_map * * used_maps, u32 len)
```

```json
{
  "name": "__bpf_free_used_maps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580915737,
      "name": "__bpf_free_used_maps",
      "external": true,
      "loc": "kernel/bpf/core.c:2102",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_free_deferred"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918064,
      "name": "__bpf_free_used_maps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __bpf_free_used_maps(struct bpf_prog_aux * aux, struct bpf_map * * used_maps, u32 len)
```

```json
{
  "name": "__bpf_free_used_maps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580919497,
      "name": "__bpf_free_used_maps",
      "external": true,
      "loc": "kernel/bpf/core.c:2198",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_free_deferred"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922000,
      "name": "__bpf_free_used_maps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __bpf_free_used_maps(struct bpf_prog_aux * aux, struct bpf_map * * used_maps, u32 len)
```

```json
{
  "name": "__bpf_free_used_maps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581122009,
      "name": "__bpf_free_used_maps",
      "external": true,
      "loc": "kernel/bpf/core.c:2218",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_free_deferred"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581124528,
      "name": "__bpf_free_used_maps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void __bpf_free_used_maps(struct bpf_prog_aux * aux, struct bpf_map * * used_maps, u32 len)
```

```json
{
  "name": "__bpf_free_used_maps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581391192,
      "name": "__bpf_free_used_maps",
      "external": true,
      "loc": "kernel/bpf/core.c:2504",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_free_deferred"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581394048,
      "name": "__bpf_free_used_maps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void __bpf_free_used_maps(struct bpf_prog_aux * aux, struct bpf_map * * used_maps, u32 len)
```

```json
{
  "name": "__bpf_free_used_maps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581740439,
      "name": "__bpf_free_used_maps",
      "external": true,
      "loc": "kernel/bpf/core.c:2498",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_free_deferred"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581743856,
      "name": "__bpf_free_used_maps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void __bpf_free_used_maps(struct bpf_prog_aux * aux, struct bpf_map * * used_maps, u32 len)
```

```json
{
  "name": "__bpf_free_used_maps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581899914,
      "name": "__bpf_free_used_maps",
      "external": true,
      "loc": "kernel/bpf/core.c:2515",
      "file": "kernel/bpf/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_prog_free_deferred"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903168,
      "name": "__bpf_free_used_maps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void __bpf_free_used_maps(struct bpf_prog_aux * aux, struct bpf_map * * used_maps, u32 len)
```

```json
{
  "name": "__bpf_free_used_maps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__bpf_free_used_maps",
      "external": true,
      "loc": "kernel/bpf/core.c:2691",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_free_deferred",
        "kernel/bpf/verifier.c:bpf_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597434215,
      "name": "__bpf_free_used_maps.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582026832,
      "name": "__bpf_free_used_maps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __bpf_free_used_maps(struct bpf_prog_aux * aux, struct bpf_map * * used_maps, u32 len)
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
