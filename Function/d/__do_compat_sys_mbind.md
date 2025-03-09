# Function: <code>__do_compat_sys_mbind</code>

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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581321792,
      "name": "__do_compat_sys_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1557",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_compat_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321792,
      "name": "__do_compat_sys_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581405984,
      "name": "__do_compat_sys_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1597",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_compat_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581405984,
      "name": "__do_compat_sys_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581518128,
      "name": "__do_compat_sys_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1643",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_compat_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581518128,
      "name": "__do_compat_sys_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581582688,
      "name": "__do_compat_sys_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1645",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_compat_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582688,
      "name": "__do_compat_sys_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581794736,
      "name": "__do_compat_sys_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1714",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_compat_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794736,
      "name": "__do_compat_sys_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581842640,
      "name": "__do_compat_sys_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1690",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_compat_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842640,
      "name": "__do_compat_sys_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581873488,
      "name": "__do_compat_sys_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1704",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_compat_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581873488,
      "name": "__do_compat_sys_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
  "name": "__do_compat_sys_mbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493020128,
      "name": "__do_compat_sys_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1645",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__arm64_compat_sys_mbind"
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
  "name": "__do_compat_sys_mbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286448656,
      "name": "__do_compat_sys_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1645",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:__se_compat_sys_mbind"
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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581551424,
      "name": "__do_compat_sys_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1645",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_compat_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581551424,
      "name": "__do_compat_sys_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581493072,
      "name": "__do_compat_sys_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1645",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_compat_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493072,
      "name": "__do_compat_sys_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581542736,
      "name": "__do_compat_sys_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1645",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_compat_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581542736,
      "name": "__do_compat_sys_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
```

```json
{
  "name": "__do_compat_sys_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581607712,
      "name": "__do_compat_sys_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1645",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__x32_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_compat_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581607712,
      "name": "__do_compat_sys_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
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
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int __do_compat_sys_mbind(compat_ulong_t start, compat_ulong_t len, compat_ulong_t mode, compat_ulong_t * nmask, compat_ulong_t maxnode, compat_ulong_t flags)
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
