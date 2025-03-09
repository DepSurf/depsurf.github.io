# Function: <code>__do_compat_sys_set_mempolicy</code>

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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
```

```json
{
  "name": "__do_compat_sys_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314416,
      "name": "__do_compat_sys_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1536",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314416,
      "name": "__do_compat_sys_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
```

```json
{
  "name": "__do_compat_sys_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581398320,
      "name": "__do_compat_sys_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1576",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581398320,
      "name": "__do_compat_sys_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
```

```json
{
  "name": "__do_compat_sys_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510416,
      "name": "__do_compat_sys_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1622",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510416,
      "name": "__do_compat_sys_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
```

```json
{
  "name": "__do_compat_sys_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581574784,
      "name": "__do_compat_sys_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1624",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574784,
      "name": "__do_compat_sys_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
```

```json
{
  "name": "__do_compat_sys_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581785120,
      "name": "__do_compat_sys_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1693",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785120,
      "name": "__do_compat_sys_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
```

```json
{
  "name": "__do_compat_sys_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581829984,
      "name": "__do_compat_sys_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1669",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581829984,
      "name": "__do_compat_sys_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
```

```json
{
  "name": "__do_compat_sys_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581860416,
      "name": "__do_compat_sys_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1683",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860416,
      "name": "__do_compat_sys_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
  "name": "__do_compat_sys_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493011232,
      "name": "__do_compat_sys_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1624",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__arm64_compat_sys_set_mempolicy"
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
  "name": "__do_compat_sys_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286438512,
      "name": "__do_compat_sys_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1624",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__se_compat_sys_set_mempolicy"
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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
```

```json
{
  "name": "__do_compat_sys_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581543520,
      "name": "__do_compat_sys_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1624",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543520,
      "name": "__do_compat_sys_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
```

```json
{
  "name": "__do_compat_sys_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581485168,
      "name": "__do_compat_sys_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1624",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485168,
      "name": "__do_compat_sys_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
```

```json
{
  "name": "__do_compat_sys_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581534832,
      "name": "__do_compat_sys_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1624",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581534832,
      "name": "__do_compat_sys_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
```

```json
{
  "name": "__do_compat_sys_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581599904,
      "name": "__do_compat_sys_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:1624",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_set_mempolicy",
        "mm/mempolicy.c:__ia32_compat_sys_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581599904,
      "name": "__do_compat_sys_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
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
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int __do_compat_sys_set_mempolicy(int mode, compat_ulong_t * nmask, compat_ulong_t maxnode)
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
