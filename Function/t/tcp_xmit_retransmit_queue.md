# Function: <code>tcp_xmit_retransmit_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586679856,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2713",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_resume_early_retransmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586679856,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 764
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
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587126704,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2754",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_resume_early_retransmit",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587126704,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 829
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
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587324464,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2874",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_resume_early_retransmit",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587324464,
      "name": "tcp_xmit_retransmit_queue.part.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
    },
    {
      "addr": 18446744071587325936,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587456464,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2919",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587456464,
      "name": "tcp_xmit_retransmit_queue.part.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
    },
    {
      "addr": 18446744071587457776,
      "name": "tcp_xmit_retransmit_queue",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587978272,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2973",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587978272,
      "name": "tcp_xmit_retransmit_queue.part.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071587979680,
      "name": "tcp_xmit_retransmit_queue",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588328368,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2954",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328368,
      "name": "tcp_xmit_retransmit_queue.part.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
    },
    {
      "addr": 18446744071588329952,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588517472,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2985",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588517472,
      "name": "tcp_xmit_retransmit_queue.part.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
    },
    {
      "addr": 18446744071588519088,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588927808,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3015",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588927808,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
    },
    {
      "addr": 18446744071588929392,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589151760,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3046",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589151760,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
    },
    {
      "addr": 18446744071589153328,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590120592,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3115",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590120592,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
    },
    {
      "addr": 18446744071590122496,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590168320,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3287",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590168320,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
    },
    {
      "addr": 18446744071590170224,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590082752,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3284",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590082752,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 834
    },
    {
      "addr": 18446744071590084672,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590857440,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3284",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590857440,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
    },
    {
      "addr": 18446744071590859264,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592493648,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3289",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592493648,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
    },
    {
      "addr": 18446744071592495616,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594348992,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3291",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594348992,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
    },
    {
      "addr": 18446744071594351088,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594736864,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3373",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594736864,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
    },
    {
      "addr": 18446744071594739008,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595542416,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3437",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595542416,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
    },
    {
      "addr": 18446744071595544528,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502767392,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3046",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502767392,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    },
    {
      "addr": 18446603336502769192,
      "name": "tcp_xmit_retransmit_queue",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235472192,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3046",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235472192,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
    },
    {
      "addr": 3235473800,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296399344,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3046",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296399344,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
    },
    {
      "addr": 13835058055296401792,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278889502,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3046",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278889502,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
    },
    {
      "addr": 18446743936278890984,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588758144,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3046",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588758144,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
    },
    {
      "addr": 18446744071588759712,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588470096,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3046",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588470096,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
    },
    {
      "addr": 18446744071588471648,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589194320,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3046",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589194320,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
    },
    {
      "addr": 18446744071589195888,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_xmit_retransmit_queue(struct sock * sk)
```

```json
{
  "name": "tcp_xmit_retransmit_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589234416,
      "name": "tcp_xmit_retransmit_queue",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3046",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589234416,
      "name": "tcp_xmit_retransmit_queue.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 671
    },
    {
      "addr": 18446744071589235984,
      "name": "tcp_xmit_retransmit_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
