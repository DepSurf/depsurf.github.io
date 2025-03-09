# Function: <code>sk_msg_free</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588181176,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:196",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_remove",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588179104,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588507181,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:205",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588505168,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588715773,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:204",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588714016,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589582861,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:205",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589580880,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589594093,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:207",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589589808,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589648327,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:207",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_stop"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589647792,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590403719,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:207",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_stop"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590403456,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591999639,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:216",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_skb_ingress_enqueue"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591999024,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593812983,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:216",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_skb_ingress_enqueue"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593810256,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594191145,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:217",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_skb_ingress_enqueue"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594184544,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594990025,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:217",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/skmsg.c:sk_psock_stop",
        "net/core/skmsg.c:sk_psock_skb_ingress_enqueue"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/xfrm/espintcp.c:espintcp_close",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594980880,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502279988,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:204",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502274272,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235020076,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:204",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235018208,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295779440,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:204",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295776512,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278512720,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:204",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278510578,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588322509,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:204",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588320752,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588035293,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:204",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588033536,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588654333,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:204",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588652576,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```

```json
{
  "name": "sk_msg_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588794141,
      "name": "sk_msg_free",
      "external": true,
      "loc": "net/core/skmsg.c:204",
      "file": "net/core/skmsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_drop",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:__sk_psock_purge_ingress_msg"
      ],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588792384,
      "name": "sk_msg_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int sk_msg_free(struct sock * sk, struct sk_msg * msg)
```
</details>
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
