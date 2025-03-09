# Function: <code>do_pselect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581080763,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:646",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:SyS_pselect6"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581243764,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:650",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:SyS_pselect6"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581321556,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:658",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:SyS_pselect6"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581376995,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:702",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:SyS_pselect6"
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
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581518473,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:701",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:SyS_pselect6"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int do_pselect(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec * tsp, const sigset_t * sigmask, size_t sigsetsize)
```

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581679488,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:703",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581679488,
      "name": "do_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581766285,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:728",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6"
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
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581883537,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:728",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__do_sys_pselect6"
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
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581955776,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:728",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955776,
      "name": "do_pselect.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582188128,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:728",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188128,
      "name": "do_pselect.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582235584,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:728",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235584,
      "name": "do_pselect.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582261408,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:728",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582261408,
      "name": "do_pselect.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582579296,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:731",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582579296,
      "name": "do_pselect.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583108080,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:732",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583108080,
      "name": "do_pselect.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583676672,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:732",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583676672,
      "name": "do_pselect.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583894416,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:732",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894416,
      "name": "do_pselect.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584101584,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:732",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584101584,
      "name": "do_pselect.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493452716,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:728",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__arm64_sys_pselect6"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int do_pselect(int n, fd_set * inp, fd_set * outp, fd_set * exp, void * tsp, const sigset_t * sigmask, size_t sigsetsize, enum poll_time_type type)
```

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227018632,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:728",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__se_sys_pselect6_time32",
        "fs/select.c:__se_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227018632,
      "name": "do_pselect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287007440,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:728",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__se_sys_pselect6"
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
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273135806,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:728",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:__se_sys_pselect6"
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
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581924512,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:728",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924512,
      "name": "do_pselect.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581862096,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:728",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581862096,
      "name": "do_pselect.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581915824,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:728",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915824,
      "name": "do_pselect.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_pselect",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581985456,
      "name": "do_pselect",
      "external": false,
      "loc": "fs/select.c:728",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__ia32_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6",
        "fs/select.c:__x64_sys_pselect6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581985456,
      "name": "do_pselect.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
long int do_pselect(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec * tsp, const sigset_t * sigmask, size_t sigsetsize)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
long int do_pselect(int n, fd_set * inp, fd_set * outp, fd_set * exp, struct timespec * tsp, const sigset_t * sigmask, size_t sigsetsize)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
long int do_pselect(int n, fd_set * inp, fd_set * outp, fd_set * exp, void * tsp, const sigset_t * sigmask, size_t sigsetsize, enum poll_time_type type)
```
</details>
</li>
</ul>
