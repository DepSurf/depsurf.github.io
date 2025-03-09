# Function: <code>skb_send_sock_locked</code>

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
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587432304,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2264",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:smap_tx_work",
        "net/core/skbuff.c:skb_send_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587432304,
      "name": "skb_send_sock_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
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
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587736624,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2280",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:smap_tx_work",
        "net/core/skbuff.c:skb_send_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587736624,
      "name": "skb_send_sock_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587870256,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2289",
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
      "addr": 18446744071587870256,
      "name": "skb_send_sock_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 635
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588174736,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2448",
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
      "addr": 18446744071588174736,
      "name": "skb_send_sock_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588379872,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2450",
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
      "addr": 18446744071588379872,
      "name": "skb_send_sock_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589241344,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2449",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/xfrm/espintcp.c:espintcp_push_msgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589241344,
      "name": "skb_send_sock_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589240624,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2466",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_psock_backlog",
        "net/xfrm/espintcp.c:espintcp_push_msgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589240624,
      "name": "skb_send_sock_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589136192,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2622",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_push_msgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589136192,
      "name": "skb_send_sock_locked",
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
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589856144,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2694",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_push_msgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589856144,
      "name": "skb_send_sock_locked",
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
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591381376,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2743",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_push_msgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591381376,
      "name": "skb_send_sock_locked",
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
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593142288,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2949",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_push_msgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593142288,
      "name": "skb_send_sock_locked",
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
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593595456,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:3121",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_push_msgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593595456,
      "name": "skb_send_sock_locked",
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
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594368368,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:3209",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/espintcp.c:espintcp_push_msgs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594368368,
      "name": "skb_send_sock_locked",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501891952,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2450",
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
      "addr": 18446603336501891952,
      "name": "skb_send_sock_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234655764,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2450",
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
      "addr": 3234655764,
      "name": "skb_send_sock_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295305744,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2450",
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
      "addr": 13835058055295305744,
      "name": "skb_send_sock_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 824
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278211910,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2450",
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
      "addr": 18446743936278211910,
      "name": "skb_send_sock_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587986656,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2450",
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
      "addr": 18446744071587986656,
      "name": "skb_send_sock_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587699760,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2450",
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
      "addr": 18446744071587699760,
      "name": "skb_send_sock_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588318432,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2450",
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
      "addr": 18446744071588318432,
      "name": "skb_send_sock_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```

```json
{
  "name": "skb_send_sock_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588453776,
      "name": "skb_send_sock_locked",
      "external": true,
      "loc": "net/core/skbuff.c:2450",
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
      "addr": 18446744071588453776,
      "name": "skb_send_sock_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 639
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int skb_send_sock_locked(struct sock * sk, struct sk_buff * skb, int offset, int len)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
