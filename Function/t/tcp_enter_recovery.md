# Function: <code>tcp_enter_recovery</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586624336,
      "name": "tcp_enter_recovery",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2641",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_resume_early_retransmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586624336,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587072112,
      "name": "tcp_enter_recovery",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2639",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_resume_early_retransmit",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587072112,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587269776,
      "name": "tcp_enter_recovery",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2693",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_resume_early_retransmit",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587269776,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587419632,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2657",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587419632,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587939472,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2599",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587939472,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588289104,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2626",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588289104,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588477744,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2617",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588477744,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588884624,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2637",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588884624,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589108704,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2643",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589108704,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590079008,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2628",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590079008,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590124736,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2740",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590124736,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590038960,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2740",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590038960,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590811808,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2774",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590811808,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592446592,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2790",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592446592,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594300784,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2801",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594300784,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594686960,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2800",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594686960,
      "name": "tcp_enter_recovery",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595491792,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2839",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595491792,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502725440,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2643",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502725440,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235429108,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2643",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235429108,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296346064,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2643",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296346064,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278852450,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2643",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278852450,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588715088,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2643",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588715088,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588427072,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2643",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427072,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589151264,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2643",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589151264,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void tcp_enter_recovery(struct sock * sk, bool ece_ack)
```

```json
{
  "name": "tcp_enter_recovery",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589191168,
      "name": "tcp_enter_recovery",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2643",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589191168,
      "name": "tcp_enter_recovery",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
