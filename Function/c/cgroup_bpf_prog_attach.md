# Function: <code>cgroup_bpf_prog_attach</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580755616,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:430",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755616,
      "name": "cgroup_bpf_prog_attach",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580820528,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:481",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820528,
      "name": "cgroup_bpf_prog_attach",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915104,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:539",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915104,
      "name": "cgroup_bpf_prog_attach",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580968560,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:549",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580968560,
      "name": "cgroup_bpf_prog_attach",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581130912,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:751",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581130912,
      "name": "cgroup_bpf_prog_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581164960,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:762",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581164960,
      "name": "cgroup_bpf_prog_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581181952,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:762",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581181952,
      "name": "cgroup_bpf_prog_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422560,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:792",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422560,
      "name": "cgroup_bpf_prog_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581748448,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:917",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581748448,
      "name": "cgroup_bpf_prog_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582163408,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1129",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582163408,
      "name": "cgroup_bpf_prog_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582360336,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1129",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582360336,
      "name": "cgroup_bpf_prog_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582527184,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:1130",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582527184,
      "name": "cgroup_bpf_prog_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492317816,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:549",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492317816,
      "name": "cgroup_bpf_prog_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226203008,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:549",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226203008,
      "name": "cgroup_bpf_prog_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285557344,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:549",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285557344,
      "name": "cgroup_bpf_prog_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272443676,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:549",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272443676,
      "name": "cgroup_bpf_prog_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580937360,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:549",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580937360,
      "name": "cgroup_bpf_prog_attach",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580883424,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:549",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580883424,
      "name": "cgroup_bpf_prog_attach",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580928608,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:549",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928608,
      "name": "cgroup_bpf_prog_attach",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_bpf_prog_attach",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580989136,
      "name": "cgroup_bpf_prog_attach",
      "external": true,
      "loc": "kernel/bpf/cgroup.c:549",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580989136,
      "name": "cgroup_bpf_prog_attach",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr * attr, enum bpf_prog_type ptype, struct bpf_prog * prog)
```
</details>
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
