# Function: <code>mptcp_bind</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int mptcp_bind(struct socket * sock, struct sockaddr * uaddr, int addr_len)
```

```json
{
  "name": "mptcp_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591076176,
      "name": "mptcp_bind",
      "external": false,
      "loc": "net/mptcp/protocol.c:1780",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591076176,
      "name": "mptcp_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int mptcp_bind(struct socket * sock, struct sockaddr * uaddr, int addr_len)
```

```json
{
  "name": "mptcp_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591141008,
      "name": "mptcp_bind",
      "external": false,
      "loc": "net/mptcp/protocol.c:3148",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591141008,
      "name": "mptcp_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int mptcp_bind(struct socket * sock, struct sockaddr * uaddr, int addr_len)
```

```json
{
  "name": "mptcp_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591072368,
      "name": "mptcp_bind",
      "external": false,
      "loc": "net/mptcp/protocol.c:3135",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591072368,
      "name": "mptcp_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int mptcp_bind(struct socket * sock, struct sockaddr * uaddr, int addr_len)
```

```json
{
  "name": "mptcp_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_bind",
      "external": false,
      "loc": "net/mptcp/protocol.c:3228",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591921072,
      "name": "mptcp_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071592752009,
      "name": "mptcp_bind.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int mptcp_bind(struct socket * sock, struct sockaddr * uaddr, int addr_len)
```

```json
{
  "name": "mptcp_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_bind",
      "external": false,
      "loc": "net/mptcp/protocol.c:3475",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593646096,
      "name": "mptcp_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071594638947,
      "name": "mptcp_bind.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int mptcp_bind(struct socket * sock, struct sockaddr * uaddr, int addr_len)
```

```json
{
  "name": "mptcp_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_bind",
      "external": false,
      "loc": "net/mptcp/protocol.c:3614",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595600896,
      "name": "mptcp_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071596369664,
      "name": "mptcp_bind.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int mptcp_bind(struct socket * sock, struct sockaddr * uaddr, int addr_len)
```

```json
{
  "name": "mptcp_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596092544,
      "name": "mptcp_bind",
      "external": false,
      "loc": "net/mptcp/protocol.c:3674",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596092544,
      "name": "mptcp_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int mptcp_bind(struct socket * sock, struct sockaddr * uaddr, int addr_len)
```

```json
{
  "name": "mptcp_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596961232,
      "name": "mptcp_bind",
      "external": false,
      "loc": "net/mptcp/protocol.c:3784",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596961232,
      "name": "mptcp_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int mptcp_bind(struct socket * sock, struct sockaddr * uaddr, int addr_len)
```
</details>
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
