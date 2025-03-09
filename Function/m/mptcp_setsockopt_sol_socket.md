# Function: <code>mptcp_setsockopt_sol_socket</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mptcp_setsockopt_sol_socket",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591144007,
      "name": "mptcp_setsockopt_sol_socket",
      "external": false,
      "loc": "net/mptcp/protocol.c:2808",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_setsockopt"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_socket(struct mptcp_sock * msk, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt_sol_socket",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591151136,
      "name": "mptcp_setsockopt_sol_socket",
      "external": false,
      "loc": "net/mptcp/sockopt.c:213",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/sockopt.c:mptcp_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591151136,
      "name": "mptcp_setsockopt_sol_socket",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
int mptcp_setsockopt_sol_socket(struct mptcp_sock * msk, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt_sol_socket",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592001824,
      "name": "mptcp_setsockopt_sol_socket",
      "external": false,
      "loc": "net/mptcp/sockopt.c:288",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/sockopt.c:mptcp_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592001824,
      "name": "mptcp_setsockopt_sol_socket",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1235
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
int mptcp_setsockopt_sol_socket(struct mptcp_sock * msk, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt_sol_socket",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593739632,
      "name": "mptcp_setsockopt_sol_socket",
      "external": false,
      "loc": "net/mptcp/sockopt.c:290",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/sockopt.c:mptcp_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593739632,
      "name": "mptcp_setsockopt_sol_socket",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1221
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
int mptcp_setsockopt_sol_socket(struct mptcp_sock * msk, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt_sol_socket",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595675376,
      "name": "mptcp_setsockopt_sol_socket",
      "external": false,
      "loc": "net/mptcp/sockopt.c:290",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/sockopt.c:mptcp_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595675376,
      "name": "mptcp_setsockopt_sol_socket",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 955
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
int mptcp_setsockopt_sol_socket(struct mptcp_sock * msk, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt_sol_socket",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596185664,
      "name": "mptcp_setsockopt_sol_socket",
      "external": false,
      "loc": "net/mptcp/sockopt.c:291",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/sockopt.c:mptcp_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596185664,
      "name": "mptcp_setsockopt_sol_socket",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
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
int mptcp_setsockopt_sol_socket(struct mptcp_sock * msk, int optname, sockptr_t optval, unsigned int optlen)
```

```json
{
  "name": "mptcp_setsockopt_sol_socket",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597060912,
      "name": "mptcp_setsockopt_sol_socket",
      "external": false,
      "loc": "net/mptcp/sockopt.c:292",
      "file": "net/mptcp/sockopt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/sockopt.c:mptcp_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597060912,
      "name": "mptcp_setsockopt_sol_socket",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1011
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int mptcp_setsockopt_sol_socket(struct mptcp_sock * msk, int optname, sockptr_t optval, unsigned int optlen)
```
</details>
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
