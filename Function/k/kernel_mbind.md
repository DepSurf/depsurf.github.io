# Function: <code>kernel_mbind</code>

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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581320048,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1315",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581320048,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1641
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581404240,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1355",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581404240,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1641
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581516400,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1401",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581516400,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1625
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580864,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1404",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580864,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1714
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581794448,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1473",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794448,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581842352,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1449",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581842352,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581873200,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1463",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581873200,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582164912,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1459",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164912,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582621952,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1452",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582621952,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583146208,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1467",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583146208,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583356528,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1484",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583356528,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583593120,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1468",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583593120,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493018664,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1404",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__arm64_compat_sys_mbind",
        "mm/mempolicy.c:__arm64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493018664,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1340
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286448240,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1404",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__se_compat_sys_mbind",
        "mm/mempolicy.c:__se_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286448240,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    }
  ]
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581549600,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1404",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581549600,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1714
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581491248,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1404",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581491248,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1714
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581540912,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1404",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581540912,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1714
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```

```json
{
  "name": "kernel_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581605936,
      "name": "kernel_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1404",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:__do_compat_sys_mbind",
        "mm/mempolicy.c:__ia32_sys_mbind",
        "mm/mempolicy.c:__x64_sys_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581605936,
      "name": "kernel_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1669
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
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int kernel_mbind(long unsigned int start, long unsigned int len, long unsigned int mode, const long unsigned int * nmask, long unsigned int maxnode, unsigned int flags)
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
