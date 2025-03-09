# Function: <code>sock_setbindtodevice_locked</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int sock_setbindtodevice_locked(struct sock * sk, int ifindex)
```

```json
{
  "name": "sock_setbindtodevice_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588148864,
      "name": "sock_setbindtodevice_locked",
      "external": false,
      "loc": "net/core/sock.c:572",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588148864,
      "name": "sock_setbindtodevice_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int sock_setbindtodevice_locked(struct sock * sk, int ifindex)
```

```json
{
  "name": "sock_setbindtodevice_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588354128,
      "name": "sock_setbindtodevice_locked",
      "external": false,
      "loc": "net/core/sock.c:572",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588354128,
      "name": "sock_setbindtodevice_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int sock_setbindtodevice_locked(struct sock * sk, int ifindex)
```

```json
{
  "name": "sock_setbindtodevice_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501865568,
      "name": "sock_setbindtodevice_locked",
      "external": false,
      "loc": "net/core/sock.c:572",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501865568,
      "name": "sock_setbindtodevice_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int sock_setbindtodevice_locked(struct sock * sk, int ifindex)
```

```json
{
  "name": "sock_setbindtodevice_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234636280,
      "name": "sock_setbindtodevice_locked",
      "external": false,
      "loc": "net/core/sock.c:572",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234636280,
      "name": "sock_setbindtodevice_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
int sock_setbindtodevice_locked(struct sock * sk, int ifindex)
```

```json
{
  "name": "sock_setbindtodevice_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295263872,
      "name": "sock_setbindtodevice_locked",
      "external": false,
      "loc": "net/core/sock.c:572",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295263872,
      "name": "sock_setbindtodevice_locked",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int sock_setbindtodevice_locked(struct sock * sk, int ifindex)
```

```json
{
  "name": "sock_setbindtodevice_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278186134,
      "name": "sock_setbindtodevice_locked",
      "external": false,
      "loc": "net/core/sock.c:572",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278186134,
      "name": "sock_setbindtodevice_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int sock_setbindtodevice_locked(struct sock * sk, int ifindex)
```

```json
{
  "name": "sock_setbindtodevice_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587960912,
      "name": "sock_setbindtodevice_locked",
      "external": false,
      "loc": "net/core/sock.c:572",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587960912,
      "name": "sock_setbindtodevice_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int sock_setbindtodevice_locked(struct sock * sk, int ifindex)
```

```json
{
  "name": "sock_setbindtodevice_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587674016,
      "name": "sock_setbindtodevice_locked",
      "external": false,
      "loc": "net/core/sock.c:572",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587674016,
      "name": "sock_setbindtodevice_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int sock_setbindtodevice_locked(struct sock * sk, int ifindex)
```

```json
{
  "name": "sock_setbindtodevice_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588292688,
      "name": "sock_setbindtodevice_locked",
      "external": false,
      "loc": "net/core/sock.c:572",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588292688,
      "name": "sock_setbindtodevice_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int sock_setbindtodevice_locked(struct sock * sk, int ifindex)
```

```json
{
  "name": "sock_setbindtodevice_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588427760,
      "name": "sock_setbindtodevice_locked",
      "external": false,
      "loc": "net/core/sock.c:572",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427760,
      "name": "sock_setbindtodevice_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int sock_setbindtodevice_locked(struct sock * sk, int ifindex)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int sock_setbindtodevice_locked(struct sock * sk, int ifindex)
```
</details>
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
