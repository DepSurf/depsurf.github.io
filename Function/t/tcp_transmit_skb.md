# Function: <code>tcp_transmit_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tcp_transmit_skb(struct sock * sk, struct sk_buff * skb, int clone_it, gfp_t gfp_mask)
```

```json
{
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586668016,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:903",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_ack",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586668016,
      "name": "tcp_transmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2352
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
int tcp_transmit_skb(struct sock * sk, struct sk_buff * skb, int clone_it, gfp_t gfp_mask)
```

```json
{
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587114352,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:901",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_send_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587114352,
      "name": "tcp_transmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2312
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
int tcp_transmit_skb(struct sock * sk, struct sk_buff * skb, int clone_it, gfp_t gfp_mask)
```

```json
{
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587312672,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:919",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_send_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587312672,
      "name": "tcp_transmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2346
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
int tcp_transmit_skb(struct sock * sk, struct sk_buff * skb, int clone_it, gfp_t gfp_mask)
```

```json
{
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587444224,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:985",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444224,
      "name": "tcp_transmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2437
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
int tcp_transmit_skb(struct sock * sk, struct sk_buff * skb, int clone_it, gfp_t gfp_mask)
```

```json
{
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587965216,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1034",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587965216,
      "name": "tcp_transmit_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2665
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588332532,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1185",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588521681,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1173",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588932115,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1171",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589156131,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1190",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590125155,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1253",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590172883,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1420",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590087315,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1420",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590862003,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1420",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592498646,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1417",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594354390,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1414",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594742294,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1416",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595547990,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1477",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502772204,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1190",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235476704,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1190",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296405636,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1190",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278893608,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1190",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588762515,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1190",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588474451,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1190",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589198691,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1190",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
  "name": "tcp_transmit_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589238803,
      "name": "tcp_transmit_skb",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1190",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_xmit_probe_skb",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_send_active_reset",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int tcp_transmit_skb(struct sock * sk, struct sk_buff * skb, int clone_it, gfp_t gfp_mask)
```
</details>
</li>
</ul>
