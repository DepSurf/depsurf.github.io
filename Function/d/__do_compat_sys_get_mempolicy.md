# Function: <code>__do_compat_sys_get_mempolicy</code>

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
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581316784,
      "name": "__do_compat_sys_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1506",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581316784,
      "name": "__do_compat_sys_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400912,
      "name": "__do_compat_sys_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1546",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400912,
      "name": "__do_compat_sys_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581513056,
      "name": "__do_compat_sys_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1592",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581513056,
      "name": "__do_compat_sys_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581577424,
      "name": "__do_compat_sys_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1594",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581577424,
      "name": "__do_compat_sys_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581787040,
      "name": "__do_compat_sys_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1663",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581787040,
      "name": "__do_compat_sys_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831984,
      "name": "__do_compat_sys_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1639",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831984,
      "name": "__do_compat_sys_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581862848,
      "name": "__do_compat_sys_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1653",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581862848,
      "name": "__do_compat_sys_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493014256,
      "name": "__do_compat_sys_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1594",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__arm64_compat_sys_get_mempolicy"
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
  "name": "__do_compat_sys_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286441236,
      "name": "__do_compat_sys_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1594",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__se_compat_sys_get_mempolicy"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581546160,
      "name": "__do_compat_sys_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1594",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581546160,
      "name": "__do_compat_sys_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487808,
      "name": "__do_compat_sys_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1594",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487808,
      "name": "__do_compat_sys_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581537472,
      "name": "__do_compat_sys_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1594",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581537472,
      "name": "__do_compat_sys_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581602512,
      "name": "__do_compat_sys_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1594",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_get_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581602512,
      "name": "__do_compat_sys_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int __do_compat_sys_get_mempolicy(int * policy, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t addr, compat_ulong_t flags)
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
