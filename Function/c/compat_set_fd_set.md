# Function: <code>compat_set_fd_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int compat_set_fd_set(long unsigned int nr, compat_ulong_t * ufdset, long unsigned int * fdset)
```

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581347888,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/compat.c:1195",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:compat_core_sys_select",
        "fs/compat.c:compat_core_sys_select",
        "fs/compat.c:compat_core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347888,
      "name": "compat_set_fd_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int compat_set_fd_set(long unsigned int nr, compat_ulong_t * ufdset, long unsigned int * fdset)
```

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581528720,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/compat.c:1198",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:compat_core_sys_select",
        "fs/compat.c:compat_core_sys_select",
        "fs/compat.c:compat_core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581528720,
      "name": "compat_set_fd_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int compat_set_fd_set(long unsigned int nr, compat_ulong_t * ufdset, long unsigned int * fdset)
```

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581614720,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/compat.c:1109",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:compat_core_sys_select",
        "fs/compat.c:compat_core_sys_select",
        "fs/compat.c:compat_core_sys_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581614720,
      "name": "compat_set_fd_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581373916,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1173",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581515404,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1164",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581673104,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1165",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581759392,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1177",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581877042,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1152",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581949298,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1152",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582180373,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1162",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582227611,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1168",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582253654,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1168",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582571558,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1171",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583100830,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1172",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583669054,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1172",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583886350,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1172",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584093518,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1172",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493444812,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1152",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287000000,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1152",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581918034,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1152",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581855618,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1152",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581909346,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1152",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
  "name": "compat_set_fd_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581978973,
      "name": "compat_set_fd_set",
      "external": false,
      "loc": "fs/select.c:1152",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select",
        "fs/select.c:compat_core_sys_select"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int compat_set_fd_set(long unsigned int nr, compat_ulong_t * ufdset, long unsigned int * fdset)
```
</details>
</li>
</ul>
