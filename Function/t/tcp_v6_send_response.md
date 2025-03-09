# Function: <code>tcp_v6_send_response</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, u32 label)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587163760,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:736",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587163760,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1209
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587616608,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:745",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587616608,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1374
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587821472,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:755",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587821472,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1478
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587978720,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:776",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587978720,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1584
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588514688,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:778",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588514688,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1562
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588881392,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:792",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588881392,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1692
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589104432,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:796",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589104432,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1671
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589557440,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:803",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589557440,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1931
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589781472,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:805",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589781472,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1955
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590804704,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:854",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590804704,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1671
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590864144,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:870",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590864144,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1693
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590792768,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:885",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590792768,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1961
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:888",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591612544,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2015
    },
    {
      "addr": 18446744071592742086,
      "name": "tcp_v6_send_response.cold",
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:841",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593305216,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2109
    },
    {
      "addr": 18446744071594628632,
      "name": "tcp_v6_send_response.cold",
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority, u32 txhash)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:848",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595209904,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2123
    },
    {
      "addr": 18446744071596362320,
      "name": "tcp_v6_send_response.cold",
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority, u32 txhash)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:845",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595604176,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1820
    },
    {
      "addr": 18446744071596890644,
      "name": "tcp_v6_send_response.cold",
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, int rst, u8 tclass, __be32 label, u32 priority, u32 txhash, struct tcp_key * key)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:863",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596449760,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2361
    },
    {
      "addr": 18446744071597815325,
      "name": "tcp_v6_send_response.cold",
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503491144,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:805",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503491144,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1444
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236136540,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:805",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236136540,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1608
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297273552,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:805",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297273552,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2000
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279461388,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:805",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279461388,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1518
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589385840,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:805",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589385840,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1955
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589110832,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:805",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589110832,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1955
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589822704,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:805",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589822704,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1955
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
void tcp_v6_send_response(const struct sock * sk, struct sk_buff * skb, u32 seq, u32 ack, u32 win, u32 tsval, u32 tsecr, int oif, struct tcp_md5sig_key * key, int rst, u8 tclass, __be32 label, u32 priority)
```

```json
{
  "name": "tcp_v6_send_response",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589873760,
      "name": "tcp_v6_send_response",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:805",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589873760,
      "name": "tcp_v6_send_response",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1999
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 label</code> ➡️ <code>__be32 label</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 priority</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 txhash</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param reordered. </b>
<code>sk, skb, seq, ack, win, tsval, tsecr, oif, key, rst, tclass, label, priority, txhash</code> ➡️ <code>sk, skb, seq, ack, win, tsval, tsecr, oif, rst, tclass, label, priority, txhash, key</code>
</li>
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
