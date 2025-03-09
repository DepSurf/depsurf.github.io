# Function: <code>mptcp_destroy_common</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void mptcp_destroy_common(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_destroy_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591168256,
      "name": "mptcp_destroy_common",
      "external": true,
      "loc": "net/mptcp/protocol.c:2786",
      "file": "net/mptcp/protocol.c",
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
      "addr": 18446744071591168256,
      "name": "mptcp_destroy_common",
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
void mptcp_destroy_common(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_destroy_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591102144,
      "name": "mptcp_destroy_common",
      "external": true,
      "loc": "net/mptcp/protocol.c:2863",
      "file": "net/mptcp/protocol.c",
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
      "addr": 18446744071591102144,
      "name": "mptcp_destroy_common",
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
void mptcp_destroy_common(struct mptcp_sock * msk)
```

```json
{
  "name": "mptcp_destroy_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591945600,
      "name": "mptcp_destroy_common",
      "external": true,
      "loc": "net/mptcp/protocol.c:2924",
      "file": "net/mptcp/protocol.c",
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
      "addr": 18446744071591945600,
      "name": "mptcp_destroy_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
void mptcp_destroy_common(struct mptcp_sock * msk, unsigned int flags)
```

```json
{
  "name": "mptcp_destroy_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593671072,
      "name": "mptcp_destroy_common",
      "external": true,
      "loc": "net/mptcp/protocol.c:3078",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_v6_destroy",
        "net/mptcp/protocol.c:mptcp_disconnect",
        "net/mptcp/subflow.c:mptcp_sock_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593671072,
      "name": "mptcp_destroy_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
void mptcp_destroy_common(struct mptcp_sock * msk, unsigned int flags)
```

```json
{
  "name": "mptcp_destroy_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595602144,
      "name": "mptcp_destroy_common",
      "external": true,
      "loc": "net/mptcp/protocol.c:3164",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595602144,
      "name": "mptcp_destroy_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
void mptcp_destroy_common(struct mptcp_sock * msk, unsigned int flags)
```

```json
{
  "name": "mptcp_destroy_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596110944,
      "name": "mptcp_destroy_common",
      "external": true,
      "loc": "net/mptcp/protocol.c:3224",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_destroy",
        "net/mptcp/protocol.c:mptcp_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596110944,
      "name": "mptcp_destroy_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
void mptcp_destroy_common(struct mptcp_sock * msk, unsigned int flags)
```

```json
{
  "name": "mptcp_destroy_common",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596983440,
      "name": "mptcp_destroy_common",
      "external": true,
      "loc": "net/mptcp/protocol.c:3322",
      "file": "net/mptcp/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_destroy",
        "net/mptcp/protocol.c:mptcp_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596983440,
      "name": "mptcp_destroy_common",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
void mptcp_destroy_common(struct mptcp_sock * msk)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
