# Function: <code>mptcp_sock_graft</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mptcp_sock_graft",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591083868,
      "name": "mptcp_sock_graft",
      "external": false,
      "loc": "net/mptcp/protocol.c:1694",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_finish_join"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mptcp_sock_graft(struct sock * sk, struct socket * parent)
```

```json
{
  "name": "mptcp_sock_graft",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591158884,
      "name": "mptcp_sock_graft",
      "external": true,
      "loc": "net/mptcp/protocol.c:3058",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_finish_join"
      ],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591169072,
      "name": "mptcp_sock_graft",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mptcp_sock_graft(struct sock * sk, struct socket * parent)
```

```json
{
  "name": "mptcp_sock_graft",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591091198,
      "name": "mptcp_sock_graft",
      "external": true,
      "loc": "net/mptcp/protocol.c:3037",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_finish_join"
      ],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591103648,
      "name": "mptcp_sock_graft",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mptcp_sock_graft(struct sock * sk, struct socket * parent)
```

```json
{
  "name": "mptcp_sock_graft",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591929403,
      "name": "mptcp_sock_graft",
      "external": true,
      "loc": "net/mptcp/protocol.c:3130",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_finish_join"
      ],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591947616,
      "name": "mptcp_sock_graft",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mptcp_sock_graft(struct sock * sk, struct socket * parent)
```

```json
{
  "name": "mptcp_sock_graft",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593651476,
      "name": "mptcp_sock_graft",
      "external": true,
      "loc": "net/mptcp/protocol.c:3308",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_finish_join",
        "net/mptcp/protocol.c:mptcp_release_cb"
      ],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593674016,
      "name": "mptcp_sock_graft",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mptcp_sock_graft(struct sock * sk, struct socket * parent)
```

```json
{
  "name": "mptcp_sock_graft",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595579048,
      "name": "mptcp_sock_graft",
      "external": true,
      "loc": "net/mptcp/protocol.c:3381",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_finish_join",
        "net/mptcp/protocol.c:mptcp_release_cb"
      ],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595605952,
      "name": "mptcp_sock_graft",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mptcp_sock_graft(struct sock * sk, struct socket * parent)
```

```json
{
  "name": "mptcp_sock_graft",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596106567,
      "name": "mptcp_sock_graft",
      "external": true,
      "loc": "net/mptcp/protocol.c:3447",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept"
      ],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596114832,
      "name": "mptcp_sock_graft",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mptcp_sock_graft(struct sock * sk, struct socket * parent)
```

```json
{
  "name": "mptcp_sock_graft",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596977093,
      "name": "mptcp_sock_graft",
      "external": true,
      "loc": "net/mptcp/protocol.c:3540",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_stream_accept"
      ],
      "caller_func": [
        "net/mptcp/subflow.c:__mptcp_subflow_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596987696,
      "name": "mptcp_sock_graft",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void mptcp_sock_graft(struct sock * sk, struct socket * parent)
```
</details>
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
