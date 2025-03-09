# Function: <code>__do_compat_sys_socketcall</code>

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
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588061131,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:844",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
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
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588237291,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:838",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588626032,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:719",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588626032,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 851
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
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588848576,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:719",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588848576,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589734224,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:544",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589734224,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589767280,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:424",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589767280,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589670816,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:424",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589670816,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590427760,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:424",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__x64_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590427760,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 869
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
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592027040,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:424",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592027040,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 876
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
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593843216,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:422",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593843216,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 876
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
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594217568,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:423",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594217568,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 934
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
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595014944,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:423",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595014944,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 934
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
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502423160,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:719",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__arm64_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502423160,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1004
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
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295975072,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:719",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__se_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295975072,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
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
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588454960,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:719",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588454960,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588167648,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:719",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588167648,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588787136,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:719",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588787136,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
long int __do_compat_sys_socketcall(int call, u32 * args)
```

```json
{
  "name": "__do_compat_sys_socketcall",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588927760,
      "name": "__do_compat_sys_socketcall",
      "external": false,
      "loc": "net/compat.c:719",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588927760,
      "name": "__do_compat_sys_socketcall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
long int __do_compat_sys_socketcall(int call, u32 * args)
```
</details>
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
long int __do_compat_sys_socketcall(int call, u32 * args)
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
long int __do_compat_sys_socketcall(int call, u32 * args)
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
