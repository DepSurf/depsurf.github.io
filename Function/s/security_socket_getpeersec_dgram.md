# Function: <code>security_socket_getpeersec_dgram</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582234944,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:1287",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:maybe_init_creds",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582234944,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582453504,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:1317",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453504,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582545968,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:1338",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582545968,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582631120,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2281",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582631120,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582784592,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2139",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582784592,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582986784,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:1448",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582986784,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583098352,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2199",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583098352,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583281552,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2218",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583281552,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583387456,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2257",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583387456,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, struct lsmblob * blob)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583729440,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2568",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583729440,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, struct lsmblob * blob)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583849648,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2585",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583849648,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, struct lsmblob * blob)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583874960,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2648",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583874960,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, struct lsmblob * blob)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584239376,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2656",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584239376,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584845568,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2686",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584845568,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585547776,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2666",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585547776,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585778400,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:4650",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585778400,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586022240,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:4816",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586022240,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495137336,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2257",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495137336,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228525256,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2257",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228525256,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289051680,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2257",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289051680,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274388000,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2257",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274388000,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583356192,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2257",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583356192,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583293296,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2257",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583293296,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583339968,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2257",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583339968,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int security_socket_getpeersec_dgram(struct socket * sock, struct sk_buff * skb, u32 * secid)
```

```json
{
  "name": "security_socket_getpeersec_dgram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583435152,
      "name": "security_socket_getpeersec_dgram",
      "external": true,
      "loc": "security/security.c:2257",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:maybe_init_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583435152,
      "name": "security_socket_getpeersec_dgram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmblob * blob</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 * secid</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 * secid</code>
</li>
<li>
<b>Param removed. </b>
<code>struct lsmblob * blob</code>
</li>
</ul>
</details>
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
