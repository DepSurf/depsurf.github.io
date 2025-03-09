# Function: <code>sk_psock_skb_redirect</code>

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
void sk_psock_skb_redirect(struct sk_buff * skb)
```

```json
{
  "name": "sk_psock_skb_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589579200,
      "name": "sk_psock_skb_redirect",
      "external": false,
      "loc": "net/core/skmsg.c:686",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_strp_read",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589579200,
      "name": "sk_psock_skb_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void sk_psock_skb_redirect(struct sk_buff * skb)
```

```json
{
  "name": "sk_psock_skb_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589589136,
      "name": "sk_psock_skb_redirect",
      "external": false,
      "loc": "net/core/skmsg.c:762",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589589136,
      "name": "sk_psock_skb_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int sk_psock_skb_redirect(struct sk_psock * from, struct sk_buff * skb)
```

```json
{
  "name": "sk_psock_skb_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589650720,
      "name": "sk_psock_skb_redirect",
      "external": false,
      "loc": "net/core/skmsg.c:885",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589650720,
      "name": "sk_psock_skb_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int sk_psock_skb_redirect(struct sk_psock * from, struct sk_buff * skb)
```

```json
{
  "name": "sk_psock_skb_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590407696,
      "name": "sk_psock_skb_redirect",
      "external": false,
      "loc": "net/core/skmsg.c:880",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590407696,
      "name": "sk_psock_skb_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int sk_psock_skb_redirect(struct sk_psock * from, struct sk_buff * skb)
```

```json
{
  "name": "sk_psock_skb_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592000176,
      "name": "sk_psock_skb_redirect",
      "external": false,
      "loc": "net/core/skmsg.c:900",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592000176,
      "name": "sk_psock_skb_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
int sk_psock_skb_redirect(struct sk_psock * from, struct sk_buff * skb)
```

```json
{
  "name": "sk_psock_skb_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593818272,
      "name": "sk_psock_skb_redirect",
      "external": false,
      "loc": "net/core/skmsg.c:907",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593818272,
      "name": "sk_psock_skb_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
int sk_psock_skb_redirect(struct sk_psock * from, struct sk_buff * skb)
```

```json
{
  "name": "sk_psock_skb_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594192688,
      "name": "sk_psock_skb_redirect",
      "external": false,
      "loc": "net/core/skmsg.c:897",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594192688,
      "name": "sk_psock_skb_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
int sk_psock_skb_redirect(struct sk_psock * from, struct sk_buff * skb)
```

```json
{
  "name": "sk_psock_skb_redirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594988112,
      "name": "sk_psock_skb_redirect",
      "external": false,
      "loc": "net/core/skmsg.c:903",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_tls_strp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594988112,
      "name": "sk_psock_skb_redirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void sk_psock_skb_redirect(struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_psock * from</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb</code> ➡️ <code>from, skb</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
