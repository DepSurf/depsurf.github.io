# Function: <code>skb_send_sock</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587432944,
      "name": "skb_send_sock",
      "external": true,
      "loc": "net/core/skbuff.c:2352",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587432944,
      "name": "skb_send_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587737280,
      "name": "skb_send_sock",
      "external": true,
      "loc": "net/core/skbuff.c:2368",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587737280,
      "name": "skb_send_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
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
int skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589168400,
      "name": "skb_send_sock",
      "external": true,
      "loc": "net/core/skbuff.c:2631",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589168400,
      "name": "skb_send_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589888928,
      "name": "skb_send_sock",
      "external": true,
      "loc": "net/core/skbuff.c:2703",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589888928,
      "name": "skb_send_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591418544,
      "name": "skb_send_sock",
      "external": true,
      "loc": "net/core/skbuff.c:2752",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591418544,
      "name": "skb_send_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593191424,
      "name": "skb_send_sock",
      "external": true,
      "loc": "net/core/skbuff.c:2958",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593191424,
      "name": "skb_send_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593649984,
      "name": "skb_send_sock",
      "external": true,
      "loc": "net/core/skbuff.c:3129",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593649984,
      "name": "skb_send_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594425760,
      "name": "skb_send_sock",
      "external": true,
      "loc": "net/core/skbuff.c:3217",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594425760,
      "name": "skb_send_sock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int skb_send_sock(struct sock * sk, struct sk_buff * skb, int offset, int len)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
