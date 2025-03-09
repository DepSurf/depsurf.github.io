# Function: <code>__skb_send_sock</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len, sendmsg_func sendmsg, sendpage_func sendpage)
```

```json
{
  "name": "__skb_send_sock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589135328,
      "name": "__skb_send_sock",
      "external": false,
      "loc": "net/core/skbuff.c:2531",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589135328,
      "name": "__skb_send_sock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 849
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
int __skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len, sendmsg_func sendmsg, sendpage_func sendpage)
```

```json
{
  "name": "__skb_send_sock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589855280,
      "name": "__skb_send_sock",
      "external": false,
      "loc": "net/core/skbuff.c:2603",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589855280,
      "name": "__skb_send_sock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 849
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
int __skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len, sendmsg_func sendmsg, sendpage_func sendpage)
```

```json
{
  "name": "__skb_send_sock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591380384,
      "name": "__skb_send_sock",
      "external": false,
      "loc": "net/core/skbuff.c:2652",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591380384,
      "name": "__skb_send_sock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 984
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
int __skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len, sendmsg_func sendmsg, sendpage_func sendpage)
```

```json
{
  "name": "__skb_send_sock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593141280,
      "name": "__skb_send_sock",
      "external": false,
      "loc": "net/core/skbuff.c:2858",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593141280,
      "name": "__skb_send_sock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 984
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
int __skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len, sendmsg_func sendmsg)
```

```json
{
  "name": "__skb_send_sock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593594128,
      "name": "__skb_send_sock",
      "external": false,
      "loc": "net/core/skbuff.c:3022",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593594128,
      "name": "__skb_send_sock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1299
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
int __skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len, sendmsg_func sendmsg)
```

```json
{
  "name": "__skb_send_sock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594367040,
      "name": "__skb_send_sock",
      "external": false,
      "loc": "net/core/skbuff.c:3110",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594367040,
      "name": "__skb_send_sock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1299
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
int __skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len, sendmsg_func sendmsg, sendpage_func sendpage)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>sendpage_func sendpage</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
