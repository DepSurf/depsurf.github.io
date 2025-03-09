# Function: <code>tcp_v4_send_ack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_v4_send_ack(struct net * net, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586688544,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:713",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586688544,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void tcp_v4_send_ack(struct net * net, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587137120,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:715",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587137120,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587342704,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:719",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587342704,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587475792,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:733",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587475792,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 713
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587999328,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:737",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587999328,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 713
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588349056,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:793",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588349056,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 798
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588535840,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:798",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588535840,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 798
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588946496,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:797",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588946496,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589170704,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:802",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589170704,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590140288,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:823",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590140288,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590188528,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:824",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590188528,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590102496,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:839",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590102496,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:839",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590879776,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
    },
    {
      "addr": 18446744071592720240,
      "name": "tcp_v4_send_ack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:845",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592518592,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1014
    },
    {
      "addr": 18446744071594606577,
      "name": "tcp_v4_send_ack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:856",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594376272,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1014
    },
    {
      "addr": 18446744071596341914,
      "name": "tcp_v4_send_ack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos, u32 txhash)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:862",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594764528,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1024
    },
    {
      "addr": 18446744071596871175,
      "name": "tcp_v4_send_ack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_key * key, int reply_flags, u8 tos, u32 txhash)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:918",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595571024,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1444
    },
    {
      "addr": 18446744071597794833,
      "name": "tcp_v4_send_ack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502788928,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:802",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502788928,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 752
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235495040,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:802",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235495040,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 876
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296427952,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:802",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296427952,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1112
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278909704,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:802",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278909704,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588777088,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:802",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588777088,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588489024,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:802",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588489024,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589213264,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:802",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589213264,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
void tcp_v4_send_ack(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int reply_flags, u8 tos)
```

```json
{
  "name": "tcp_v4_send_ack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589254512,
      "name": "tcp_v4_send_ack",
      "external": false,
      "loc": "net/ipv4/tcp_ipv4.c:802",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589254512,
      "name": "tcp_v4_send_ack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sock * sk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct net * net</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 txhash</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct tcp_md5sig_key * key</code> ➡️ <code>struct tcp_key * key</code>
</li>
</ul>
</details>
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
