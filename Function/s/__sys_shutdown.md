# Function: <code>__sys_shutdown</code>

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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587706256,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:1969",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587706256,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587839712,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:1956",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__x32_compat_sys_socketcall",
        "net/compat.c:__ia32_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587839712,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588143616,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2151",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588143616,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588348512,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2151",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588348512,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589207040,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2194",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589207040,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589206192,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2189",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589206192,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589099856,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2183",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589099856,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589817504,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2256",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817504,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591337632,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2331",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591337632,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593093024,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2323",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593093024,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593545200,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2360",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593545200,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594317488,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2430",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__do_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594317488,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501854896,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2151",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__arm64_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501854896,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234623240,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2151",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234623240,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295257136,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2151",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_socketcall",
        "net/socket.c:__se_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295257136,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278183108,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2151",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__se_sys_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278183108,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587955296,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2151",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587955296,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587668400,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2151",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587668400,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588287072,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2151",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588287072,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int __sys_shutdown(int fd, int how)
```

```json
{
  "name": "__sys_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588422224,
      "name": "__sys_shutdown",
      "external": true,
      "loc": "net/socket.c:2151",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/socket.c:__ia32_sys_socketcall",
        "net/socket.c:__x64_sys_socketcall",
        "net/socket.c:__ia32_sys_shutdown",
        "net/socket.c:__x64_sys_shutdown",
        "net/compat.c:__do_compat_sys_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588422224,
      "name": "__sys_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int __sys_shutdown(int fd, int how)
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
