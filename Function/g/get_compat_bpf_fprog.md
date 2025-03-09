# Function: <code>get_compat_bpf_fprog</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```

```json
{
  "name": "get_compat_bpf_fprog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586885760,
      "name": "get_compat_bpf_fprog",
      "external": true,
      "loc": "net/compat.c:313",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:compat_sock_setsockopt",
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586885760,
      "name": "get_compat_bpf_fprog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```

```json
{
  "name": "get_compat_bpf_fprog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587079840,
      "name": "get_compat_bpf_fprog",
      "external": true,
      "loc": "net/compat.c:313",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:compat_sock_setsockopt",
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587079840,
      "name": "get_compat_bpf_fprog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```

```json
{
  "name": "get_compat_bpf_fprog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587208112,
      "name": "get_compat_bpf_fprog",
      "external": true,
      "loc": "net/compat.c:312",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587208112,
      "name": "get_compat_bpf_fprog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```

```json
{
  "name": "get_compat_bpf_fprog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587722432,
      "name": "get_compat_bpf_fprog",
      "external": true,
      "loc": "net/compat.c:319",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587722432,
      "name": "get_compat_bpf_fprog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```

```json
{
  "name": "get_compat_bpf_fprog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588056000,
      "name": "get_compat_bpf_fprog",
      "external": true,
      "loc": "net/compat.c:319",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__compat_sys_setsockopt",
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588056000,
      "name": "get_compat_bpf_fprog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```

```json
{
  "name": "get_compat_bpf_fprog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588231920,
      "name": "get_compat_bpf_fprog",
      "external": true,
      "loc": "net/compat.c:319",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__compat_sys_setsockopt",
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588231920,
      "name": "get_compat_bpf_fprog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```

```json
{
  "name": "get_compat_bpf_fprog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588624448,
      "name": "get_compat_bpf_fprog",
      "external": true,
      "loc": "net/compat.c:321",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__compat_sys_setsockopt",
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588624448,
      "name": "get_compat_bpf_fprog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```

```json
{
  "name": "get_compat_bpf_fprog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588846992,
      "name": "get_compat_bpf_fprog",
      "external": true,
      "loc": "net/compat.c:321",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__compat_sys_setsockopt",
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588846992,
      "name": "get_compat_bpf_fprog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```

```json
{
  "name": "get_compat_bpf_fprog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589732688,
      "name": "get_compat_bpf_fprog",
      "external": true,
      "loc": "net/compat.c:340",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__compat_sys_setsockopt",
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589732688,
      "name": "get_compat_bpf_fprog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```

```json
{
  "name": "get_compat_bpf_fprog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502422000,
      "name": "get_compat_bpf_fprog",
      "external": true,
      "loc": "net/compat.c:321",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__compat_sys_setsockopt",
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502422000,
      "name": "get_compat_bpf_fprog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```

```json
{
  "name": "get_compat_bpf_fprog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295973360,
      "name": "get_compat_bpf_fprog",
      "external": true,
      "loc": "net/compat.c:321",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__compat_sys_setsockopt",
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295973360,
      "name": "get_compat_bpf_fprog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```

```json
{
  "name": "get_compat_bpf_fprog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588453376,
      "name": "get_compat_bpf_fprog",
      "external": true,
      "loc": "net/compat.c:321",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__compat_sys_setsockopt",
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588453376,
      "name": "get_compat_bpf_fprog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```

```json
{
  "name": "get_compat_bpf_fprog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588166064,
      "name": "get_compat_bpf_fprog",
      "external": true,
      "loc": "net/compat.c:321",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__compat_sys_setsockopt",
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588166064,
      "name": "get_compat_bpf_fprog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```

```json
{
  "name": "get_compat_bpf_fprog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588785552,
      "name": "get_compat_bpf_fprog",
      "external": true,
      "loc": "net/compat.c:321",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__compat_sys_setsockopt",
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588785552,
      "name": "get_compat_bpf_fprog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```

```json
{
  "name": "get_compat_bpf_fprog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588926176,
      "name": "get_compat_bpf_fprog",
      "external": true,
      "loc": "net/compat.c:321",
      "file": "net/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/compat.c:__compat_sys_setsockopt",
        "net/packet/af_packet.c:compat_packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588926176,
      "name": "get_compat_bpf_fprog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct sock_fprog * get_compat_bpf_fprog(char * optval)
```
</details>
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct sock_fprog * get_compat_bpf_fprog(char * optval)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct sock_fprog * get_compat_bpf_fprog(char * optval)
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
struct sock_fprog * get_compat_bpf_fprog(char * optval)
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
