# Function: <code>mptcp_token_destroy</code>

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
void mptcp_token_destroy(u32 token)
```

```json
{
  "name": "mptcp_token_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591107904,
      "name": "mptcp_token_destroy",
      "external": true,
      "loc": "net/mptcp/token.c:191",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_v6_destroy",
        "net/mptcp/subflow.c:mptcp_sock_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591107904,
      "name": "mptcp_token_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void mptcp_token_destroy(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_token_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591190752,
      "name": "mptcp_token_destroy",
      "external": true,
      "loc": "net/mptcp/token.c:367",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:mptcp_check_fastclose"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591190752,
      "name": "mptcp_token_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void mptcp_token_destroy(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_token_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591128128,
      "name": "mptcp_token_destroy",
      "external": true,
      "loc": "net/mptcp/token.c:367",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591128128,
      "name": "mptcp_token_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void mptcp_token_destroy(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_token_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591976048,
      "name": "mptcp_token_destroy",
      "external": true,
      "loc": "net/mptcp/token.c:371",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591976048,
      "name": "mptcp_token_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void mptcp_token_destroy(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_token_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593705296,
      "name": "mptcp_token_destroy",
      "external": true,
      "loc": "net/mptcp/token.c:371",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593705296,
      "name": "mptcp_token_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void mptcp_token_destroy(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_token_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595639184,
      "name": "mptcp_token_destroy",
      "external": true,
      "loc": "net/mptcp/token.c:371",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_connect",
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595639184,
      "name": "mptcp_token_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void mptcp_token_destroy(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_token_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596147552,
      "name": "mptcp_token_destroy",
      "external": true,
      "loc": "net/mptcp/token.c:375",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_connect",
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596147552,
      "name": "mptcp_token_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void mptcp_token_destroy(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_token_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597021264,
      "name": "mptcp_token_destroy",
      "external": true,
      "loc": "net/mptcp/token.c:375",
      "file": "net/mptcp/token.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_connect",
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:mptcp_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597021264,
      "name": "mptcp_token_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
void mptcp_token_destroy(u32 token)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mptcp_sock * msk</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 token</code>
</li>
</ul>
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
