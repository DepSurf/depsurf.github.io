# Function: <code>mptcp_subflow_get_send</code>

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
struct sock * mptcp_subflow_get_send(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_subflow_get_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591082928,
      "name": "mptcp_subflow_get_send",
      "external": false,
      "loc": "net/mptcp/protocol.c:695",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591082928,
      "name": "mptcp_subflow_get_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
struct sock * mptcp_subflow_get_send(struct mptcp_sock * msk, u32 * sndbuf)
```

```json
{
  "name": "mptcp_subflow_get_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591146496,
      "name": "mptcp_subflow_get_send",
      "external": false,
      "loc": "net/mptcp/protocol.c:1362",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591146496,
      "name": "mptcp_subflow_get_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 894
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct sock * mptcp_subflow_get_send(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_subflow_get_send",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591078224,
      "name": "mptcp_subflow_get_send",
      "external": false,
      "loc": "net/mptcp/protocol.c:1414",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_check_push",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591078224,
      "name": "mptcp_subflow_get_send.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
    },
    {
      "addr": 18446744071591078912,
      "name": "mptcp_subflow_get_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct sock * mptcp_subflow_get_send(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_subflow_get_send",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591936208,
      "name": "mptcp_subflow_get_send",
      "external": false,
      "loc": "net/mptcp/protocol.c:1434",
      "file": "net/mptcp/protocol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_check_push",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591936208,
      "name": "mptcp_subflow_get_send.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 870
    },
    {
      "addr": 18446744071591937088,
      "name": "mptcp_subflow_get_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct sock * mptcp_subflow_get_send(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_subflow_get_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_subflow_get_send",
      "external": false,
      "loc": "net/mptcp/protocol.c:1439",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_check_push",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593661376,
      "name": "mptcp_subflow_get_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1166
    },
    {
      "addr": 18446744071594640054,
      "name": "mptcp_subflow_get_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
struct sock * mptcp_subflow_get_send(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_subflow_get_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_subflow_get_send",
      "external": false,
      "loc": "net/mptcp/protocol.c:1400",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595591824,
      "name": "mptcp_subflow_get_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1166
    },
    {
      "addr": 18446744071596369296,
      "name": "mptcp_subflow_get_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct sock * mptcp_subflow_get_send(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_subflow_get_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_subflow_get_send",
      "external": false,
      "loc": "net/mptcp/protocol.c:1371",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596100960,
      "name": "mptcp_subflow_get_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1165
    },
    {
      "addr": 18446744071596898860,
      "name": "mptcp_subflow_get_send.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
struct sock * mptcp_subflow_get_send(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_subflow_get_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596971904,
      "name": "mptcp_subflow_get_send",
      "external": true,
      "loc": "net/mptcp/protocol.c:1400",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/sched.c:mptcp_sched_get_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596971904,
      "name": "mptcp_subflow_get_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
struct sock * mptcp_subflow_get_send(struct mptcp_sock * msk)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 * sndbuf</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 * sndbuf</code>
</li>
</ul>
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
