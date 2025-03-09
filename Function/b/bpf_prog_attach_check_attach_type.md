# Function: <code>bpf_prog_attach_check_attach_type</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580630404,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1488",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_attach"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580697670,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1682",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
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
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580769846,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1851",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
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
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580819928,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1874",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_prog_attach_check_attach_type(const struct bpf_prog * prog, enum bpf_attach_type attach_type)
```

```json
{
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580926864,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2751",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926864,
      "name": "bpf_prog_attach_check_attach_type",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int bpf_prog_attach_check_attach_type(const struct bpf_prog * prog, enum bpf_attach_type attach_type)
```

```json
{
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580923104,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2888",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923104,
      "name": "bpf_prog_attach_check_attach_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int bpf_prog_attach_check_attach_type(const struct bpf_prog * prog, enum bpf_attach_type attach_type)
```

```json
{
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580926464,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:2910",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926464,
      "name": "bpf_prog_attach_check_attach_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int bpf_prog_attach_check_attach_type(const struct bpf_prog * prog, enum bpf_attach_type attach_type)
```

```json
{
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581129520,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:3093",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581129520,
      "name": "bpf_prog_attach_check_attach_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int bpf_prog_attach_check_attach_type(const struct bpf_prog * prog, enum bpf_attach_type attach_type)
```

```json
{
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581398816,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:3340",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581398816,
      "name": "bpf_prog_attach_check_attach_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int bpf_prog_attach_check_attach_type(const struct bpf_prog * prog, enum bpf_attach_type attach_type)
```

```json
{
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749264,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:3374",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749264,
      "name": "bpf_prog_attach_check_attach_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int bpf_prog_attach_check_attach_type(const struct bpf_prog * prog, enum bpf_attach_type attach_type)
```

```json
{
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581909312,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:3505",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909312,
      "name": "bpf_prog_attach_check_attach_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int bpf_prog_attach_check_attach_type(const struct bpf_prog * prog, enum bpf_attach_type attach_type)
```

```json
{
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582033520,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:3809",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_prog_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582033520,
      "name": "bpf_prog_attach_check_attach_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492143412,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1874",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
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
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226039096,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1874",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
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
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285350132,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1874",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
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
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272305280,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1874",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
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
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580788728,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1874",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
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
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580734904,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1874",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
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
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580779976,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1874",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
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
  "name": "bpf_prog_attach_check_attach_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580838219,
      "name": "bpf_prog_attach_check_attach_type",
      "external": false,
      "loc": "kernel/bpf/syscall.c:1874",
      "file": "kernel/bpf/syscall.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bpf_prog_attach_check_attach_type(const struct bpf_prog * prog, enum bpf_attach_type attach_type)
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
