# Function: <code>__skb_ext_alloc</code>

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
struct skb_ext * __skb_ext_alloc(gfp_t flags)
```

```json
{
  "name": "__skb_ext_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589282448,
      "name": "__skb_ext_alloc",
      "external": true,
      "loc": "net/core/skbuff.c:6098",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_ext_add",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_subflow_get_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589282448,
      "name": "__skb_ext_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct skb_ext * __skb_ext_alloc(gfp_t flags)
```

```json
{
  "name": "__skb_ext_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589282480,
      "name": "__skb_ext_alloc",
      "external": true,
      "loc": "net/core/skbuff.c:6235",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_ext_add",
        "net/mptcp/protocol.c:__mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589282480,
      "name": "__skb_ext_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct skb_ext * __skb_ext_alloc(gfp_t flags)
```

```json
{
  "name": "__skb_ext_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589176432,
      "name": "__skb_ext_alloc",
      "external": true,
      "loc": "net/core/skbuff.c:6323",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_ext_add",
        "net/mptcp/protocol.c:__mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589176432,
      "name": "__skb_ext_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct skb_ext * __skb_ext_alloc(gfp_t flags)
```

```json
{
  "name": "__skb_ext_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589897344,
      "name": "__skb_ext_alloc",
      "external": true,
      "loc": "net/core/skbuff.c:6398",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_ext_add",
        "net/mptcp/protocol.c:mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:mptcp_alloc_tx_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589897344,
      "name": "__skb_ext_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct skb_ext * __skb_ext_alloc(gfp_t flags)
```

```json
{
  "name": "__skb_ext_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591426256,
      "name": "__skb_ext_alloc",
      "external": true,
      "loc": "net/core/skbuff.c:6311",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_ext_add",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591426256,
      "name": "__skb_ext_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct skb_ext * __skb_ext_alloc(gfp_t flags)
```

```json
{
  "name": "__skb_ext_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593192816,
      "name": "__skb_ext_alloc",
      "external": true,
      "loc": "net/core/skbuff.c:6512",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_ext_add",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593192816,
      "name": "__skb_ext_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct skb_ext * __skb_ext_alloc(gfp_t flags)
```

```json
{
  "name": "__skb_ext_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593652064,
      "name": "__skb_ext_alloc",
      "external": true,
      "loc": "net/core/skbuff.c:6557",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_ext_add",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593652064,
      "name": "__skb_ext_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct skb_ext * __skb_ext_alloc(gfp_t flags)
```

```json
{
  "name": "__skb_ext_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594427840,
      "name": "__skb_ext_alloc",
      "external": true,
      "loc": "net/core/skbuff.c:6704",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_ext_add",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594427840,
      "name": "__skb_ext_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
struct skb_ext * __skb_ext_alloc(gfp_t flags)
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
