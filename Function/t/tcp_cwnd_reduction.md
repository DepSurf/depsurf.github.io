# Function: <code>tcp_cwnd_reduction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock * sk, const int prior_unsacked, int fast_rexmit, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586622736,
      "name": "tcp_cwnd_reduction",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2472",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586622736,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587094700,
      "name": "tcp_cwnd_reduction",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2473",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_ack"
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
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587292219,
      "name": "tcp_cwnd_reduction",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:2524",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_ack"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587419456,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2489",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587419456,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587939296,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2434",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587939296,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588288896,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2461",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588288896,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588477536,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2452",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588477536,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588884416,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2472",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588884416,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589108496,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2478",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589108496,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590078800,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2463",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590078800,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int newly_lost, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590124512,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2567",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590124512,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int newly_lost, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590038736,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2567",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590038736,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int newly_lost, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590811584,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2601",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590811584,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int newly_lost, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592446336,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2614",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592446336,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int newly_lost, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594300512,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2625",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594300512,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int newly_lost, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594686688,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2624",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594686688,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int newly_lost, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595491520,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2663",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595491520,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502725160,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2478",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502725160,
      "name": "tcp_cwnd_reduction",
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235428748,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2478",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235428748,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296345776,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2478",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296345776,
      "name": "tcp_cwnd_reduction",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278852222,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2478",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278852222,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588714880,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2478",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588714880,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588426864,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2478",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588426864,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589151056,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2478",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589151056,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```

```json
{
  "name": "tcp_cwnd_reduction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589190960,
      "name": "tcp_cwnd_reduction",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2478",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589190960,
      "name": "tcp_cwnd_reduction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void tcp_cwnd_reduction(struct sock * sk, const int prior_unsacked, int fast_rexmit, int flag)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void tcp_cwnd_reduction(struct sock * sk, int newly_acked_sacked, int flag)
```
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int newly_lost</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, newly_acked_sacked, flag</code> ➡️ <code>sk, newly_acked_sacked, newly_lost, flag</code>
</li>
</ul>
</details>
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
