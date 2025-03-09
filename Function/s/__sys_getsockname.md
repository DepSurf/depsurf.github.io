# Function: <code>__sys_getsockname</code>

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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587704432,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1695",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587704432,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587837888,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1682",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587837888,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588141792,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1847",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588141792,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588346688,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1847",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588346688,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589205216,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1890",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589205216,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589203248,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1870",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589203248,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589096816,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1861",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589096816,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589814464,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1934",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589814464,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591334288,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:2014",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591334288,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593089344,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:2011",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593089344,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593541504,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:2041",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593541504,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594314160,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:2083",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594314160,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501853408,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1847",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__arm64_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501853408,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234621012,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1847",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_getsockname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234621012,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295255360,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1847",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_socketcall",
        "net/socket.c:__se_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295255360,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278181252,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1847",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_getsockname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278181252,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587953472,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1847",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587953472,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587666576,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1847",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587666576,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588285248,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1847",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588285248,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
```

```json
{
  "name": "__sys_getsockname",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588420400,
      "name": "__sys_getsockname",
      "external": true,
      "loc": "net/socket.c:1847",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_getsockname",
        "net/socket.c:__x64_sys_getsockname",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588420400,
      "name": "__sys_getsockname",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int __sys_getsockname(int fd, struct sockaddr * usockaddr, int * usockaddr_len)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
