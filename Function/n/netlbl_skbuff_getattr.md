# Function: <code>netlbl_skbuff_getattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587282848,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1064",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587282848,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587749696,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1363",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587749696,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587964912,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1363",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587964912,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588123040,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1363",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588123040,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588670864,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1363",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588670864,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589037424,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1363",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589037424,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589263424,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1364",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589263424,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589718688,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1350",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589718688,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589942992,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1350",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589942992,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590972640,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1356",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590972640,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591037424,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1356",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_from_netlbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591037424,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590968000,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1356",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_from_netlbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590968000,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591805536,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1356",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_from_netlbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591805536,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593517088,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1358",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_from_netlbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593517088,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595437040,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1358",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_from_netlbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595437040,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595944000,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1359",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_from_netlbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595944000,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596805824,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1359",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_from_netlbl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596805824,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503673808,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1350",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503673808,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236310964,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1350",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236310964,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297498448,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1350",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297498448,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279610436,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1350",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279610436,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589546592,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1350",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589546592,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589271168,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1350",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589271168,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589988624,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1350",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589988624,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int netlbl_skbuff_getattr(const struct sk_buff * skb, u16 family, struct netlbl_lsm_secattr * secattr)
```

```json
{
  "name": "netlbl_skbuff_getattr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590038512,
      "name": "netlbl_skbuff_getattr",
      "external": true,
      "loc": "net/netlabel/netlabel_kapi.c:1350",
      "file": "net/netlabel/netlabel_kapi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb",
        "security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid",
        "security/smack/smack_lsm.c:smack_inet_conn_request",
        "security/smack/smack_lsm.c:smack_socket_getpeersec_dgram",
        "security/smack/smack_lsm.c:smack_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590038512,
      "name": "netlbl_skbuff_getattr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
