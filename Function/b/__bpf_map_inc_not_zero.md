# Function: <code>__bpf_map_inc_not_zero</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580813408,
      "name": "__bpf_map_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:689",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580813408,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580922928,
      "name": "__bpf_map_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:955",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922928,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919184,
      "name": "__bpf_map_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:968",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919184,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580923120,
      "name": "__bpf_map_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:969",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923120,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125728,
      "name": "__bpf_map_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:996",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125728,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581396880,
      "name": "__bpf_map_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1231",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581396880,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581747152,
      "name": "__bpf_map_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1274",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581747152,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581934704,
      "name": "__bpf_map_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1351",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581934704,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582061328,
      "name": "__bpf_map_inc_not_zero",
      "external": true,
      "loc": "kernel/bpf/syscall.c:1382",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582061328,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492133704,
      "name": "__bpf_map_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:689",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492133704,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226032684,
      "name": "__bpf_map_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:689",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226022536,
      "name": "__bpf_map_inc_not_zero.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 3226032684,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285341888,
      "name": "__bpf_map_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:689",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285341888,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272299882,
      "name": "__bpf_map_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:689",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272299882,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580782208,
      "name": "__bpf_map_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:689",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580782208,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580728384,
      "name": "__bpf_map_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:689",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580728384,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580773456,
      "name": "__bpf_map_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:689",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773456,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```

```json
{
  "name": "__bpf_map_inc_not_zero",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580831680,
      "name": "__bpf_map_inc_not_zero",
      "external": false,
      "loc": "kernel/bpf/syscall.c:689",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_inc_not_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831680,
      "name": "__bpf_map_inc_not_zero",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct bpf_map * __bpf_map_inc_not_zero(struct bpf_map * map, bool uref)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
