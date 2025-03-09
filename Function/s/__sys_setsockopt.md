# Function: <code>__sys_setsockopt</code>

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
int __sys_setsockopt(int fd, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587692768,
      "name": "__sys_setsockopt",
      "external": false,
      "loc": "net/socket.c:1893",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587692768,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int __sys_setsockopt(int fd, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587826864,
      "name": "__sys_setsockopt",
      "external": false,
      "loc": "net/socket.c:1880",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587826864,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int __sys_setsockopt(int fd, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588136096,
      "name": "__sys_setsockopt",
      "external": false,
      "loc": "net/socket.c:2045",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588136096,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int __sys_setsockopt(int fd, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588343536,
      "name": "__sys_setsockopt",
      "external": false,
      "loc": "net/socket.c:2045",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588343536,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int __sys_setsockopt(int fd, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589196752,
      "name": "__sys_setsockopt",
      "external": false,
      "loc": "net/socket.c:2088",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589196752,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int __sys_setsockopt(int fd, int level, int optname, char * user_optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589205072,
      "name": "__sys_setsockopt",
      "external": true,
      "loc": "net/socket.c:2078",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589205072,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int __sys_setsockopt(int fd, int level, int optname, char * user_optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589098656,
      "name": "__sys_setsockopt",
      "external": true,
      "loc": "net/socket.c:2069",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589098656,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int __sys_setsockopt(int fd, int level, int optname, char * user_optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589816304,
      "name": "__sys_setsockopt",
      "external": true,
      "loc": "net/socket.c:2142",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589816304,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int __sys_setsockopt(int fd, int level, int optname, char * user_optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591336336,
      "name": "__sys_setsockopt",
      "external": true,
      "loc": "net/socket.c:2217",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591336336,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
int __sys_setsockopt(int fd, int level, int optname, char * user_optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593091664,
      "name": "__sys_setsockopt",
      "external": true,
      "loc": "net/socket.c:2209",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593091664,
      "name": "__sys_setsockopt",
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
int __sys_setsockopt(int fd, int level, int optname, char * user_optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593543840,
      "name": "__sys_setsockopt",
      "external": true,
      "loc": "net/socket.c:2242",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593543840,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int __sys_setsockopt(int fd, int level, int optname, char * user_optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594316608,
      "name": "__sys_setsockopt",
      "external": true,
      "loc": "net/socket.c:2322",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594316608,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
  "name": "__sys_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__sys_setsockopt",
      "external": false,
      "loc": "net/socket.c:2045",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__arm64_sys_setsockopt"
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
  "name": "__sys_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234622472,
      "name": "__sys_setsockopt",
      "external": false,
      "loc": "net/socket.c:2045",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__se_sys_setsockopt"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295231264,
      "name": "__sys_setsockopt",
      "external": false,
      "loc": "net/socket.c:2045",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_socketcall",
        "net/socket.c:__se_sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295231264,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278182578,
      "name": "__sys_setsockopt",
      "external": false,
      "loc": "net/socket.c:2045",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:__se_sys_setsockopt"
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
int __sys_setsockopt(int fd, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587950320,
      "name": "__sys_setsockopt",
      "external": false,
      "loc": "net/socket.c:2045",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587950320,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int __sys_setsockopt(int fd, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587663424,
      "name": "__sys_setsockopt",
      "external": false,
      "loc": "net/socket.c:2045",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587663424,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int __sys_setsockopt(int fd, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588282096,
      "name": "__sys_setsockopt",
      "external": false,
      "loc": "net/socket.c:2045",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588282096,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int __sys_setsockopt(int fd, int level, int optname, char * optval, int optlen)
```

```json
{
  "name": "__sys_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588417248,
      "name": "__sys_setsockopt",
      "external": false,
      "loc": "net/socket.c:2045",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_setsockopt",
        "net/socket.c:__x64_sys_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588417248,
      "name": "__sys_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int __sys_setsockopt(int fd, int level, int optname, char * optval, int optlen)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * user_optval</code>
</li>
<li>
<b>Param removed. </b>
<code>char * optval</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char * optval, int optlen)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char * optval, int optlen)
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
int __sys_setsockopt(int fd, int level, int optname, char * optval, int optlen)
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
