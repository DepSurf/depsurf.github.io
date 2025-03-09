# Function: <code>tcp_init_congestion_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586711408,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:182",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586711408,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587159120,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:182",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587159120,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587358160,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:183",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587358160,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587491104,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:179",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_cong.c:tcp_reinit_congestion_control",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587491104,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588013392,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:176",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_reinit_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588013392,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588364608,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:176",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_reinit_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588364608,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588554992,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:176",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_reinit_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588554992,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588966080,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:177",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_reinit_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588966080,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589190544,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:177",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_reinit_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589190544,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590162064,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:177",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_reinit_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590162064,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590211152,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:177",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590211152,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590125296,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:177",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590125296,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:177",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592721402,
      "name": "tcp_init_congestion_control.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071590902848,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:187",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594607672,
      "name": "tcp_init_congestion_control.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071592541968,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:187",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596343001,
      "name": "tcp_init_congestion_control.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071594400704,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:239",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596872116,
      "name": "tcp_init_congestion_control.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071594789616,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:239",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_set_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597796117,
      "name": "tcp_init_congestion_control.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071595601008,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502808680,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:177",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_reinit_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502808680,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235511532,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:177",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_reinit_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235511532,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296452240,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:177",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_reinit_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296452240,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278924908,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:177",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_reinit_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278924908,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588796928,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:177",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_reinit_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588796928,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588508864,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:177",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_reinit_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588508864,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589233104,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:177",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_reinit_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589233104,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void tcp_init_congestion_control(struct sock * sk)
```

```json
{
  "name": "tcp_init_congestion_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589273344,
      "name": "tcp_init_congestion_control",
      "external": true,
      "loc": "net/ipv4/tcp_cong.c:177",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_init_transfer",
        "net/ipv4/tcp_cong.c:tcp_reinit_congestion_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589273344,
      "name": "tcp_init_congestion_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
