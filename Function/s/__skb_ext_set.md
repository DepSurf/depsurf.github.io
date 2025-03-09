# Function: <code>__skb_ext_set</code>

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
void * __skb_ext_set(struct sk_buff * skb, enum skb_ext_id id, struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589282960,
      "name": "__skb_ext_set",
      "external": true,
      "loc": "net/core/skbuff.c:6148",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589282960,
      "name": "__skb_ext_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void * __skb_ext_set(struct sk_buff * skb, enum skb_ext_id id, struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589282992,
      "name": "__skb_ext_set",
      "external": true,
      "loc": "net/core/skbuff.c:6285",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589282992,
      "name": "__skb_ext_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void * __skb_ext_set(struct sk_buff * skb, enum skb_ext_id id, struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589176928,
      "name": "__skb_ext_set",
      "external": true,
      "loc": "net/core/skbuff.c:6373",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:__mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589176928,
      "name": "__skb_ext_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void * __skb_ext_set(struct sk_buff * skb, enum skb_ext_id id, struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__skb_ext_set",
      "external": true,
      "loc": "net/core/skbuff.c:6448",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:mptcp_alloc_tx_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592694852,
      "name": "__skb_ext_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589898064,
      "name": "__skb_ext_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void * __skb_ext_set(struct sk_buff * skb, enum skb_ext_id id, struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__skb_ext_set",
      "external": true,
      "loc": "net/core/skbuff.c:6361",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594580320,
      "name": "__skb_ext_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591427008,
      "name": "__skb_ext_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void * __skb_ext_set(struct sk_buff * skb, enum skb_ext_id id, struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__skb_ext_set",
      "external": true,
      "loc": "net/core/skbuff.c:6562",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596322208,
      "name": "__skb_ext_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593193280,
      "name": "__skb_ext_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void * __skb_ext_set(struct sk_buff * skb, enum skb_ext_id id, struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__skb_ext_set",
      "external": true,
      "loc": "net/core/skbuff.c:6607",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596852130,
      "name": "__skb_ext_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071593652528,
      "name": "__skb_ext_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void * __skb_ext_set(struct sk_buff * skb, enum skb_ext_id id, struct skb_ext * ext)
```

```json
{
  "name": "__skb_ext_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__skb_ext_set",
      "external": true,
      "loc": "net/core/skbuff.c:6754",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597777016,
      "name": "__skb_ext_set.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071594428304,
      "name": "__skb_ext_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void * __skb_ext_set(struct sk_buff * skb, enum skb_ext_id id, struct skb_ext * ext)
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
