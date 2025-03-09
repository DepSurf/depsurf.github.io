# Function: <code>selinux_netlbl_socket_connect_helper</code>

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
int selinux_netlbl_socket_connect_helper(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583135856,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:559",
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
      "addr": 18446744071583135856,
      "name": "selinux_netlbl_socket_connect_helper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
int selinux_netlbl_socket_connect_helper(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583251872,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:560",
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
      "addr": 18446744071583251872,
      "name": "selinux_netlbl_socket_connect_helper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int selinux_netlbl_socket_connect_helper(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583438928,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:542",
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
      "addr": 18446744071583438928,
      "name": "selinux_netlbl_socket_connect_helper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int selinux_netlbl_socket_connect_helper(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583544832,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:542",
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
      "addr": 18446744071583544832,
      "name": "selinux_netlbl_socket_connect_helper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583897442,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:542",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584017522,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:542",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584045514,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:542",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584416714,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:542",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585044566,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:545",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585763750,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:545",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585994326,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:544",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586241670,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:545",
      "file": "security/selinux/netlabel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_helper(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495317032,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:542",
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
      "addr": 18446603336495317032,
      "name": "selinux_netlbl_socket_connect_helper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int selinux_netlbl_socket_connect_helper(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228694684,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:542",
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
      "addr": 3228694684,
      "name": "selinux_netlbl_socket_connect_helper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int selinux_netlbl_socket_connect_helper(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289307232,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:542",
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
      "addr": 13835058055289307232,
      "name": "selinux_netlbl_socket_connect_helper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int selinux_netlbl_socket_connect_helper(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274533300,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:542",
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
      "addr": 18446743936274533300,
      "name": "selinux_netlbl_socket_connect_helper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int selinux_netlbl_socket_connect_helper(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583513568,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:542",
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
      "addr": 18446744071583513568,
      "name": "selinux_netlbl_socket_connect_helper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int selinux_netlbl_socket_connect_helper(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583450624,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:542",
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
      "addr": 18446744071583450624,
      "name": "selinux_netlbl_socket_connect_helper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int selinux_netlbl_socket_connect_helper(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583497344,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:542",
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
      "addr": 18446744071583497344,
      "name": "selinux_netlbl_socket_connect_helper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int selinux_netlbl_socket_connect_helper(struct sock * sk, struct sockaddr * addr)
```

```json
{
  "name": "selinux_netlbl_socket_connect_helper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583593712,
      "name": "selinux_netlbl_socket_connect_helper",
      "external": false,
      "loc": "security/selinux/netlabel.c:542",
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
      "addr": 18446744071583593712,
      "name": "selinux_netlbl_socket_connect_helper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int selinux_netlbl_socket_connect_helper(struct sock * sk, struct sockaddr * addr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int selinux_netlbl_socket_connect_helper(struct sock * sk, struct sockaddr * addr)
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
