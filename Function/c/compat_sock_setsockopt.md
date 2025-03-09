# Function: <code>compat_sock_setsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int compat_sock_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586440816,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:354",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586440816,
      "name": "compat_sock_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
int compat_sock_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586886528,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:367",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586886528,
      "name": "compat_sock_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
int compat_sock_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```

```json
{
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587080608,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:367",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587080608,
      "name": "compat_sock_setsockopt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587208928,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:366",
      "file": "net/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587208928,
      "name": "compat_sock_setsockopt.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587723264,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:373",
      "file": "net/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:compat_SyS_socketcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587723264,
      "name": "compat_sock_setsockopt.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588058005,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:373",
      "file": "net/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/compat.c:__compat_sys_setsockopt"
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
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588233822,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:373",
      "file": "net/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/compat.c:__compat_sys_setsockopt"
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
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588625837,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:353",
      "file": "net/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/compat.c:__compat_sys_setsockopt"
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
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588848381,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:353",
      "file": "net/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/compat.c:__compat_sys_setsockopt"
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
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589734029,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:372",
      "file": "net/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/compat.c:__compat_sys_setsockopt"
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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502422984,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:353",
      "file": "net/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/compat.c:__compat_sys_setsockopt"
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
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295974832,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:353",
      "file": "net/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/compat.c:__compat_sys_setsockopt"
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
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588454765,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:353",
      "file": "net/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/compat.c:__compat_sys_setsockopt"
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
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588167453,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:353",
      "file": "net/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/compat.c:__compat_sys_setsockopt"
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
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588786941,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:353",
      "file": "net/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/compat.c:__compat_sys_setsockopt"
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
  "name": "compat_sock_setsockopt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588927565,
      "name": "compat_sock_setsockopt",
      "external": false,
      "loc": "net/compat.c:353",
      "file": "net/compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/compat.c:__compat_sys_setsockopt"
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
int compat_sock_setsockopt(struct socket * sock, int level, int optname, char * optval, unsigned int optlen)
```
</details>
</li>
</ul>
