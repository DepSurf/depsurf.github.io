# Function: <code>selinux_skb_peerlbl_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269024,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:3988",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269024,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582485296,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4119",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582485296,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582577936,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4194",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582577936,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582669296,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4168",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669296,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582824000,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4183",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582824000,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4449",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015504,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071583050365,
      "name": "selinux_skb_peerlbl_sid.cold.76",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4169",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583131312,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071583163990,
      "name": "selinux_skb_peerlbl_sid.cold.72",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4357",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583318288,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071583351366,
      "name": "selinux_skb_peerlbl_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4415",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583423616,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071583457334,
      "name": "selinux_skb_peerlbl_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4408",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583764016,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071583800606,
      "name": "selinux_skb_peerlbl_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4424",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583883328,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071591363016,
      "name": "selinux_skb_peerlbl_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4588",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583909776,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071591305799,
      "name": "selinux_skb_peerlbl_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4573",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584273456,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071592293895,
      "name": "selinux_skb_peerlbl_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4477",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_process_new_assoc",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584890112,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071594075932,
      "name": "selinux_skb_peerlbl_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585597536,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4495",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_process_new_assoc",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585597536,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585828416,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4456",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_process_new_assoc",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585828416,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586076864,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4544",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_process_new_assoc",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586076864,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495180856,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4415",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495180856,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228568180,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4415",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228568180,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289121424,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4415",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289121424,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274421288,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4415",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274421288,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4415",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583392352,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071583426070,
      "name": "selinux_skb_peerlbl_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4415",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583329440,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071583363142,
      "name": "selinux_skb_peerlbl_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4415",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583376128,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071583409846,
      "name": "selinux_skb_peerlbl_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int selinux_skb_peerlbl_sid(struct sk_buff * skb, u16 family, u32 * sid)
```

```json
{
  "name": "selinux_skb_peerlbl_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "selinux_skb_peerlbl_sid",
      "external": false,
      "loc": "security/selinux/hooks.c:4415",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_postroute",
        "security/selinux/hooks.c:selinux_ip_forward",
        "security/selinux/hooks.c:selinux_inet_conn_established",
        "security/selinux/hooks.c:selinux_inet_conn_request",
        "security/selinux/hooks.c:selinux_sctp_assoc_request",
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram",
        "security/selinux/hooks.c:selinux_socket_sock_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583469296,
      "name": "selinux_skb_peerlbl_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071583506006,
      "name": "selinux_skb_peerlbl_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
