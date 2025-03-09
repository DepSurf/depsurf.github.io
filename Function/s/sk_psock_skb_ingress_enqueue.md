# Function: <code>sk_psock_skb_ingress_enqueue</code>

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
int sk_psock_skb_ingress_enqueue(struct sk_buff * skb, struct sk_psock * psock, struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_psock_skb_ingress_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589585968,
      "name": "sk_psock_skb_ingress_enqueue",
      "external": false,
      "loc": "net/core/skmsg.c:421",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589585968,
      "name": "sk_psock_skb_ingress_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int sk_psock_skb_ingress_enqueue(struct sk_buff * skb, struct sk_psock * psock, struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_psock_skb_ingress_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589645296,
      "name": "sk_psock_skb_ingress_enqueue",
      "external": false,
      "loc": "net/core/skmsg.c:519",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589645296,
      "name": "sk_psock_skb_ingress_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
int sk_psock_skb_ingress_enqueue(struct sk_buff * skb, u32 off, u32 len, struct sk_psock * psock, struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_psock_skb_ingress_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590406896,
      "name": "sk_psock_skb_ingress_enqueue",
      "external": false,
      "loc": "net/core/skmsg.c:510",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590406896,
      "name": "sk_psock_skb_ingress_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int sk_psock_skb_ingress_enqueue(struct sk_buff * skb, u32 off, u32 len, struct sk_psock * psock, struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_psock_skb_ingress_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591999072,
      "name": "sk_psock_skb_ingress_enqueue",
      "external": false,
      "loc": "net/core/skmsg.c:519",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591999072,
      "name": "sk_psock_skb_ingress_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int sk_psock_skb_ingress_enqueue(struct sk_buff * skb, u32 off, u32 len, struct sk_psock * psock, struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_psock_skb_ingress_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593815504,
      "name": "sk_psock_skb_ingress_enqueue",
      "external": false,
      "loc": "net/core/skmsg.c:526",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593815504,
      "name": "sk_psock_skb_ingress_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int sk_psock_skb_ingress_enqueue(struct sk_buff * skb, u32 off, u32 len, struct sk_psock * psock, struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_psock_skb_ingress_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594188080,
      "name": "sk_psock_skb_ingress_enqueue",
      "external": false,
      "loc": "net/core/skmsg.c:525",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594188080,
      "name": "sk_psock_skb_ingress_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int sk_psock_skb_ingress_enqueue(struct sk_buff * skb, u32 off, u32 len, struct sk_psock * psock, struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_psock_skb_ingress_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594984192,
      "name": "sk_psock_skb_ingress_enqueue",
      "external": false,
      "loc": "net/core/skmsg.c:525",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/core/skmsg.c:sk_psock_skb_ingress_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594984192,
      "name": "sk_psock_skb_ingress_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int sk_psock_skb_ingress_enqueue(struct sk_buff * skb, struct sk_psock * psock, struct sock * sk, struct sk_msg * msg)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 off</code>
</li>
<li>
<b>Param added. </b>
<code>u32 len</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, psock, sk, msg</code> ➡️ <code>skb, off, len, psock, sk, msg</code>
</li>
</ul>
</details>
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
