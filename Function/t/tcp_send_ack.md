# Function: <code>tcp_send_ack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586677168,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3342",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586677168,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587123616,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3394",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587123616,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587321392,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3520",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587321392,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587459793,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3540",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587453504,
      "name": "tcp_send_ack.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071587453808,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587981700,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3605",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587975248,
      "name": "tcp_send_ack.part.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071587975536,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588332083,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3622",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588332112,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588521219,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3654",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588521248,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588931665,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3689",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588931712,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589155681,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3721",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589155728,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590124715,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3794",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/mptcp/options.c:mptcp_incoming_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590124752,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590172432,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3978",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/options.c:check_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590172480,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590086875,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3975",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_send_ack",
        "net/mptcp/options.c:check_fully_established",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590086912,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590861563,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3976",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_subflow_send_ack",
        "net/mptcp/options.c:check_fully_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590861600,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592498124,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3985",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_send_challenge_ack",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:__mptcp_subflow_send_ack",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/options.c:check_fully_established",
        "net/mptcp/pm.c:mptcp_pm_mp_fail_received"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592498160,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594353820,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3987",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:__tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_send_challenge_ack",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/options.c:check_fully_established",
        "net/mptcp/pm.c:mptcp_pm_mp_fail_received"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594353872,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594741724,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:4076",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:__tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_send_challenge_ack",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_send_ack",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/options.c:check_fully_established",
        "net/mptcp/pm.c:mptcp_pm_mp_fail_received"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594741776,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595547423,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:4236",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_release_cb"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:__tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_send_challenge_ack",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_send_ack",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/options.c:check_fully_established",
        "net/mptcp/pm.c:mptcp_pm_mp_fail_received"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595547472,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502771620,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3721",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502771664,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235476220,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3721",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235476248,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296404928,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3721",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296405040,
      "name": "tcp_send_ack",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278893120,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3721",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278893178,
      "name": "tcp_send_ack",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588762065,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3721",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588762112,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588474001,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3721",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588474048,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589198241,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3721",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589198288,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void tcp_send_ack(struct sock * sk)
```

```json
{
  "name": "tcp_send_ack",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589238359,
      "name": "tcp_send_ack",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3721",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_cleanup_rbuf",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:__tcp_ack_snd_check",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_send_dupack",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_timer.c:tcp_compressed_ack_kick",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589238400,
      "name": "tcp_send_ack",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
