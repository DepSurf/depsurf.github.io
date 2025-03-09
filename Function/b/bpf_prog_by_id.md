# Function: <code>bpf_prog_by_id</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct bpf_prog * bpf_prog_by_id(u32 id)
```

```json
{
  "name": "bpf_prog_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580949225,
      "name": "bpf_prog_by_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3038",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": [
        "net/core/dev.c:dev_xdp_uninstall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580949680,
      "name": "bpf_prog_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct bpf_prog * bpf_prog_by_id(u32 id)
```

```json
{
  "name": "bpf_prog_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580946597,
      "name": "bpf_prog_by_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3201",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580948224,
      "name": "bpf_prog_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct bpf_prog * bpf_prog_by_id(u32 id)
```

```json
{
  "name": "bpf_prog_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580948934,
      "name": "bpf_prog_by_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3224",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952000,
      "name": "bpf_prog_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct bpf_prog * bpf_prog_by_id(u32 id)
```

```json
{
  "name": "bpf_prog_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581153645,
      "name": "bpf_prog_by_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3407",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581156832,
      "name": "bpf_prog_by_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct bpf_prog * bpf_prog_by_id(u32 id)
```

```json
{
  "name": "bpf_prog_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581429207,
      "name": "bpf_prog_by_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3665",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432832,
      "name": "bpf_prog_by_id",
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
struct bpf_prog * bpf_prog_by_id(u32 id)
```

```json
{
  "name": "bpf_prog_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581781916,
      "name": "bpf_prog_by_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3708",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581786112,
      "name": "bpf_prog_by_id",
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
struct bpf_prog * bpf_prog_by_id(u32 id)
```

```json
{
  "name": "bpf_prog_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581944534,
      "name": "bpf_prog_by_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:3844",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581947280,
      "name": "bpf_prog_by_id",
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
struct bpf_prog * bpf_prog_by_id(u32 id)
```

```json
{
  "name": "bpf_prog_by_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582071584,
      "name": "bpf_prog_by_id",
      "external": true,
      "loc": "kernel/bpf/syscall.c:4181",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf"
      ],
      "caller_func": [
        "kernel/bpf/mprog.c:bpf_mprog_tuple_relative"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073744,
      "name": "bpf_prog_by_id",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct bpf_prog * bpf_prog_by_id(u32 id)
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
