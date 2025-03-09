# Function: <code>security_bpf_prog</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582807216,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:2457",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582807216,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583001392,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:1770",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583001392,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583114720,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:2530",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583114720,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583301552,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:2547",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583301552,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583406112,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:2586",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406112,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583746352,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:2957",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583746352,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583866672,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:2975",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583866672,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583892832,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:3038",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892832,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584256656,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:3046",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584256656,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584868576,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:3124",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584868576,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585573760,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:3104",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585573760,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585805024,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:5526",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805024,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586053472,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:5667",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586053472,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495159840,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:2586",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495159840,
      "name": "security_bpf_prog",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228547192,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:2586",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228547192,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289094496,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:2586",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289094496,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274404936,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:2586",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274404936,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583374848,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:2586",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583374848,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583311952,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:2586",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583311952,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583358624,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:2586",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583358624,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_bpf_prog(struct bpf_prog * prog)
```

```json
{
  "name": "security_bpf_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583453808,
      "name": "security_bpf_prog",
      "external": true,
      "loc": "security/security.c:2586",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/inode.c:bpf_prog_get_type_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583453808,
      "name": "security_bpf_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int security_bpf_prog(struct bpf_prog * prog)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
