# Function: <code>selinux_netlbl_socket_connect_locked</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583138574,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:599",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138496,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583254686,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:600",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583254608,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583441743,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:582",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583441664,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583547647,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:582",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583547568,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583897376,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:582",
      "file": "security/selinux/netlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583897376,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584017456,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:582",
      "file": "security/selinux/netlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017456,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584045456,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:582",
      "file": "security/selinux/netlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584045456,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584416656,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:582",
      "file": "security/selinux/netlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584416656,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585044496,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:585",
      "file": "security/selinux/netlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sctp_bind_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585044496,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585763680,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:585",
      "file": "security/selinux/netlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sctp_bind_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585763680,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585994256,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:584",
      "file": "security/selinux/netlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sctp_bind_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585994256,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586241600,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:585",
      "file": "security/selinux/netlabel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_sctp_bind_connect",
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586241600,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495320248,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:582",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495320112,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228697876,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:582",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228697772,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289311864,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:582",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289311728,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274536050,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:582",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274535936,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583516383,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:582",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583516304,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583453439,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:582",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583453360,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583500159,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:582",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583500080,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583596527,
      "name": "selinux_netlbl_socket_connect_locked",
      "external": true,
      "loc": "security/selinux/netlabel.c:582",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583596448,
      "name": "selinux_netlbl_socket_connect_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int selinux_netlbl_socket_connect_locked(struct sock * sk, struct sockaddr * addr)
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
