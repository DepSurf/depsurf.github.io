# Function: <code>bpf_charge_memlock</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int bpf_charge_memlock(struct user_struct * user, u32 pages)
```

```json
{
  "name": "bpf_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580686576,
      "name": "bpf_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:184",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_charge_memlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580686576,
      "name": "bpf_charge_memlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int bpf_charge_memlock(struct user_struct * user, u32 pages)
```

```json
{
  "name": "bpf_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580753952,
      "name": "bpf_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:183",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_charge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753952,
      "name": "bpf_charge_memlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int bpf_charge_memlock(struct user_struct * user, u32 pages)
```

```json
{
  "name": "bpf_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580804544,
      "name": "bpf_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:186",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_charge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580804544,
      "name": "bpf_charge_memlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int bpf_charge_memlock(struct user_struct * user, u32 pages)
```

```json
{
  "name": "bpf_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580936309,
      "name": "bpf_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:340",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_charge_memlock"
      ],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_charge_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922576,
      "name": "bpf_charge_memlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int bpf_charge_memlock(struct user_struct * user, u32 pages)
```

```json
{
  "name": "bpf_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492123936,
      "name": "bpf_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:186",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_charge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492123936,
      "name": "bpf_charge_memlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int bpf_charge_memlock(struct user_struct * user, u32 pages)
```

```json
{
  "name": "bpf_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226020996,
      "name": "bpf_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:186",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_charge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226020996,
      "name": "bpf_charge_memlock",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "bpf_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285339736,
      "name": "bpf_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:186",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_charge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_init"
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
  "name": "bpf_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272298630,
      "name": "bpf_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:186",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_charge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_init"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int bpf_charge_memlock(struct user_struct * user, u32 pages)
```

```json
{
  "name": "bpf_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580773344,
      "name": "bpf_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:186",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_charge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773344,
      "name": "bpf_charge_memlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int bpf_charge_memlock(struct user_struct * user, u32 pages)
```

```json
{
  "name": "bpf_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580719520,
      "name": "bpf_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:186",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_charge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580719520,
      "name": "bpf_charge_memlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int bpf_charge_memlock(struct user_struct * user, u32 pages)
```

```json
{
  "name": "bpf_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580764592,
      "name": "bpf_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:186",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_charge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764592,
      "name": "bpf_charge_memlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int bpf_charge_memlock(struct user_struct * user, u32 pages)
```

```json
{
  "name": "bpf_charge_memlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580822752,
      "name": "bpf_charge_memlock",
      "external": false,
      "loc": "kernel/bpf/syscall.c:186",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_charge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822752,
      "name": "bpf_charge_memlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int bpf_charge_memlock(struct user_struct * user, u32 pages)
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
int bpf_charge_memlock(struct user_struct * user, u32 pages)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int bpf_charge_memlock(struct user_struct * user, u32 pages)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int bpf_charge_memlock(struct user_struct * user, u32 pages)
```
</details>
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
