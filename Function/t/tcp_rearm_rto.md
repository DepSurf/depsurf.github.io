# Function: <code>tcp_rearm_rto</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586630512,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3006",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_resume_early_retransmit",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_resume_early_retransmit",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_output.c:tcp_schedule_loss_probe",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586630512,
      "name": "tcp_rearm_rto.part.56",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446744071586651776,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587106043,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3011",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_resume_early_retransmit"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_resume_early_retransmit",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_schedule_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587078720,
      "name": "tcp_rearm_rto.part.60",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071587096272,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587303677,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3011",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_resume_early_retransmit"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_resume_early_retransmit",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_schedule_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587276496,
      "name": "tcp_rearm_rto.part.61",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071587293872,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587434908,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2990",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587411344,
      "name": "tcp_rearm_rto.part.60",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071587424752,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587956196,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2935",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587928832,
      "name": "tcp_rearm_rto.part.60",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071587944896,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588291968,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2973",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588291968,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588480512,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2965",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588480512,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588887552,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2985",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588887552,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589111632,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2991",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589111632,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590082336,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2975",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590082336,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590128080,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3091",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590128080,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590042464,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3098",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590042464,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590815312,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3132",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590815312,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592450000,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3148",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592450000,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594304208,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3159",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594304208,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594690416,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3158",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594690416,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595495248,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3200",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595495248,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502727752,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2991",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502727752,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235446216,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2991",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235417512,
      "name": "tcp_rearm_rto.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    },
    {
      "addr": 3235434264,
      "name": "tcp_rearm_rto",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296366848,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2991",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296331552,
      "name": "tcp_rearm_rto.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 13835058055296352208,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278866672,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2991",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278842492,
      "name": "tcp_rearm_rto.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446743936278856588,
      "name": "tcp_rearm_rto",
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588718016,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2991",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588718016,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588430000,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2991",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588430000,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589154192,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2991",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589154192,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void tcp_rearm_rto(struct sock * sk)
```

```json
{
  "name": "tcp_rearm_rto",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589194096,
      "name": "tcp_rearm_rto",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2991",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synrecv_state_fastopen",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589194096,
      "name": "tcp_rearm_rto",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
