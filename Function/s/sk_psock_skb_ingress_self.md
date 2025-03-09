# Function: <code>sk_psock_skb_ingress_self</code>

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
int sk_psock_skb_ingress_self(struct sk_psock * psock, struct sk_buff * skb)
```

```json
{
  "name": "sk_psock_skb_ingress_self",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589589264,
      "name": "sk_psock_skb_ingress_self",
      "external": false,
      "loc": "net/core/skmsg.c:483",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589589264,
      "name": "sk_psock_skb_ingress_self",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int sk_psock_skb_ingress_self(struct sk_psock * psock, struct sk_buff * skb)
```

```json
{
  "name": "sk_psock_skb_ingress_self",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589647824,
      "name": "sk_psock_skb_ingress_self",
      "external": false,
      "loc": "net/core/skmsg.c:583",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589647824,
      "name": "sk_psock_skb_ingress_self",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int sk_psock_skb_ingress_self(struct sk_psock * psock, struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "sk_psock_skb_ingress_self",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590407248,
      "name": "sk_psock_skb_ingress_self",
      "external": false,
      "loc": "net/core/skmsg.c:577",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590407248,
      "name": "sk_psock_skb_ingress_self",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int sk_psock_skb_ingress_self(struct sk_psock * psock, struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "sk_psock_skb_ingress_self",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591999840,
      "name": "sk_psock_skb_ingress_self",
      "external": false,
      "loc": "net/core/skmsg.c:590",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591999840,
      "name": "sk_psock_skb_ingress_self",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int sk_psock_skb_ingress_self(struct sk_psock * psock, struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "sk_psock_skb_ingress_self",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593815856,
      "name": "sk_psock_skb_ingress_self",
      "external": false,
      "loc": "net/core/skmsg.c:597",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593815856,
      "name": "sk_psock_skb_ingress_self",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int sk_psock_skb_ingress_self(struct sk_psock * psock, struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "sk_psock_skb_ingress_self",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594188432,
      "name": "sk_psock_skb_ingress_self",
      "external": false,
      "loc": "net/core/skmsg.c:596",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594188432,
      "name": "sk_psock_skb_ingress_self",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int sk_psock_skb_ingress_self(struct sk_psock * psock, struct sk_buff * skb, u32 off, u32 len)
```

```json
{
  "name": "sk_psock_skb_ingress_self",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594984544,
      "name": "sk_psock_skb_ingress_self",
      "external": false,
      "loc": "net/core/skmsg.c:596",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594984544,
      "name": "sk_psock_skb_ingress_self",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int sk_psock_skb_ingress_self(struct sk_psock * psock, struct sk_buff * skb)
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
