# Function: <code>sk_wmem_free_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586611448,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1430",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586632175,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1430",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586673667,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1430",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586695527,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1430",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587056067,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1347",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587082087,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1347",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587128926,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1347",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587144300,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1347",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587251991,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1403",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587277530,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1403",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587327390,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1403",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587334825,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1403",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587383687,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1406",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587409409,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1406",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587459107,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1406",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587467912,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1406",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587915237,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1410",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587932168,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1410",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587980991,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1410",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588263557,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1425",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588281208,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1425",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588331263,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1425",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588451797,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1463",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588469063,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1463",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588520412,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1463",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588857093,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1467",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588877215,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1467",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588930692,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1467",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589080661,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589101436,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589154673,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void sk_wmem_free_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590045033,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1525",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590071499,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1525",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590123915,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1525",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590101248,
      "name": "sk_wmem_free_skb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071590104384,
      "name": "sk_wmem_free_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void sk_wmem_free_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590086415,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1541",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590116818,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1541",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590171643,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1541",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590148160,
      "name": "sk_wmem_free_skb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071590151328,
      "name": "sk_wmem_free_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void sk_wmem_free_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590001167,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1557",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590015000,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1557",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590086091,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1557",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590062288,
      "name": "sk_wmem_free_skb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071590066336,
      "name": "sk_wmem_free_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void sk_wmem_free_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590771647,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1567",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590786584,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1567",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590860731,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1567",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590836128,
      "name": "sk_wmem_free_skb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071590840096,
      "name": "sk_wmem_free_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502697052,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502721072,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502770664,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235398388,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 3235419660,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3235475256,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296308484,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296337300,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296403664,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278826566,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278845766,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278892266,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588687045,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588707820,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588761057,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588399029,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588419804,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588472993,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589123221,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589143996,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589197233,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sk_wmem_free_skb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589163045,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589183836,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589237345,
      "name": "sk_wmem_free_skb",
      "external": false,
      "loc": "include/net/sock.h:1477",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void sk_wmem_free_skb(struct sock * sk, struct sk_buff * skb)
```
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
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void sk_wmem_free_skb(struct sock * sk, struct sk_buff * skb)
```
</details>
</li>
</ul>
