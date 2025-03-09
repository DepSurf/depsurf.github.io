# Function: <code>SyS_getsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_getsockopt(long int fd, long int level, long int optname, long int optval, long int optlen)
```

```json
{
  "name": "SyS_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586181840,
      "name": "SyS_getsockopt",
      "external": true,
      "loc": "net/socket.c:1765",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:SyS_socketcall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586181840,
      "name": "SyS_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_getsockopt(long int fd, long int level, long int optname, long int optval, long int optlen)
```

```json
{
  "name": "SyS_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586605724,
      "name": "SyS_getsockopt",
      "external": true,
      "loc": "net/socket.c:1758",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:SyS_socketcall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602272,
      "name": "SyS_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_getsockopt(long int fd, long int level, long int optname, long int optval, long int optlen)
```

```json
{
  "name": "SyS_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586790172,
      "name": "SyS_getsockopt",
      "external": true,
      "loc": "net/socket.c:1801",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:SyS_socketcall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586786720,
      "name": "SyS_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_getsockopt(long int fd, long int level, long int optname, long int optval, long int optlen)
```

```json
{
  "name": "SyS_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586913366,
      "name": "SyS_getsockopt",
      "external": true,
      "loc": "net/socket.c:1851",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:SyS_socketcall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586910736,
      "name": "SyS_getsockopt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_getsockopt(long int fd, long int level, long int optname, long int optval, long int optlen)
```

```json
{
  "name": "SyS_getsockopt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587405286,
      "name": "SyS_getsockopt",
      "external": true,
      "loc": "net/socket.c:1844",
      "file": "net/socket.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/socket.c:SyS_socketcall"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587402640,
      "name": "SyS_getsockopt",
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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
long int SyS_getsockopt(long int fd, long int level, long int optname, long int optval, long int optlen)
```
</details>
</li>
</ul>
