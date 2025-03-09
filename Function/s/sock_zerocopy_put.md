# Function: <code>sock_zerocopy_put</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_zerocopy_put(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587446480,
      "name": "sock_zerocopy_put",
      "external": true,
      "loc": "net/core/skbuff.c:1080",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587446480,
      "name": "sock_zerocopy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_zerocopy_put(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587750752,
      "name": "sock_zerocopy_put",
      "external": true,
      "loc": "net/core/skbuff.c:1081",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587750752,
      "name": "sock_zerocopy_put",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_zerocopy_put(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587884832,
      "name": "sock_zerocopy_put",
      "external": true,
      "loc": "net/core/skbuff.c:1083",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:sock_zerocopy_put_abort",
        "net/core/skbuff.c:skb_release_data",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884832,
      "name": "sock_zerocopy_put",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_zerocopy_put(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588190032,
      "name": "sock_zerocopy_put",
      "external": true,
      "loc": "net/core/skbuff.c:1245",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:sock_zerocopy_put_abort",
        "net/core/skbuff.c:skb_release_data",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588190032,
      "name": "sock_zerocopy_put",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_zerocopy_put(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588395200,
      "name": "sock_zerocopy_put",
      "external": true,
      "loc": "net/core/skbuff.c:1245",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:sock_zerocopy_put_abort",
        "net/core/skbuff.c:skb_release_data",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588395200,
      "name": "sock_zerocopy_put",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_zerocopy_put(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589255120,
      "name": "sock_zerocopy_put",
      "external": true,
      "loc": "net/core/skbuff.c:1244",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:sock_zerocopy_put_abort",
        "net/core/skbuff.c:skb_release_data",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589255120,
      "name": "sock_zerocopy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void sock_zerocopy_put(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589254288,
      "name": "sock_zerocopy_put",
      "external": true,
      "loc": "net/core/skbuff.c:1255",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:sock_zerocopy_put_abort",
        "net/core/skbuff.c:skb_release_data",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589254288,
      "name": "sock_zerocopy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void sock_zerocopy_put(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501911088,
      "name": "sock_zerocopy_put",
      "external": true,
      "loc": "net/core/skbuff.c:1245",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501911088,
      "name": "sock_zerocopy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void sock_zerocopy_put(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234672108,
      "name": "sock_zerocopy_put",
      "external": true,
      "loc": "net/core/skbuff.c:1245",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:sock_zerocopy_put_abort",
        "net/core/skbuff.c:skb_release_data",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234672108,
      "name": "sock_zerocopy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void sock_zerocopy_put(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295324976,
      "name": "sock_zerocopy_put",
      "external": true,
      "loc": "net/core/skbuff.c:1245",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:sock_zerocopy_put_abort",
        "net/core/skbuff.c:skb_release_data",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295324976,
      "name": "sock_zerocopy_put",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void sock_zerocopy_put(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278229900,
      "name": "sock_zerocopy_put",
      "external": true,
      "loc": "net/core/skbuff.c:1245",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278224046,
      "name": "sock_zerocopy_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446743936278224114,
      "name": "sock_zerocopy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void sock_zerocopy_put(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588001984,
      "name": "sock_zerocopy_put",
      "external": true,
      "loc": "net/core/skbuff.c:1245",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:sock_zerocopy_put_abort",
        "net/core/skbuff.c:skb_release_data",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588001984,
      "name": "sock_zerocopy_put",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void sock_zerocopy_put(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587715072,
      "name": "sock_zerocopy_put",
      "external": true,
      "loc": "net/core/skbuff.c:1245",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:sock_zerocopy_put_abort",
        "net/core/skbuff.c:skb_release_data",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587715072,
      "name": "sock_zerocopy_put",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void sock_zerocopy_put(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588333760,
      "name": "sock_zerocopy_put",
      "external": true,
      "loc": "net/core/skbuff.c:1245",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:sock_zerocopy_put_abort",
        "net/core/skbuff.c:skb_release_data",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588333760,
      "name": "sock_zerocopy_put",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void sock_zerocopy_put(struct ubuf_info * uarg)
```

```json
{
  "name": "sock_zerocopy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588469248,
      "name": "sock_zerocopy_put",
      "external": true,
      "loc": "net/core/skbuff.c:1245",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:sock_zerocopy_put_abort",
        "net/core/skbuff.c:skb_release_data",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588469248,
      "name": "sock_zerocopy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void sock_zerocopy_put(struct ubuf_info * uarg)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void sock_zerocopy_put(struct ubuf_info * uarg)
```
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
