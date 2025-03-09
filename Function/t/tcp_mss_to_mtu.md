# Function: <code>tcp_mss_to_mtu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586666528,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1326",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_mtup_init",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666528,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587112832,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1341",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtup_init",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587112832,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587308928,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1363",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtup_init",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587308928,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587450185,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1442",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587436592,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587961536,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1496",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtup_init",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587961536,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588311376,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1487",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtup_init",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588311376,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588500464,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1475",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_mtup_init",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588500464,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588909504,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1488",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtup_init",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588909504,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589144397,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1507",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589129264,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590103519,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1570",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590102656,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590150479,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1737",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590149600,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590064059,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1738",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590063680,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590837755,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1738",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590830608,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592473835,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1734",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592466032,
      "name": "tcp_mss_to_mtu",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594329451,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1731",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594320480,
      "name": "tcp_mss_to_mtu",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594715979,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1723",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594706896,
      "name": "tcp_mss_to_mtu",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595534856,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1776",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595511328,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502760240,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1507",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502744664,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235453132,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1507",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtup_init",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235453132,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296390208,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1507",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296370080,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278883372,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1507",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278869180,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588750781,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1507",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588735648,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588462733,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1507",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588447632,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589186957,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1507",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589171824,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int tcp_mss_to_mtu(struct sock * sk, int mss)
```

```json
{
  "name": "tcp_mss_to_mtu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589227021,
      "name": "tcp_mss_to_mtu",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1507",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtup_init"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589211856,
      "name": "tcp_mss_to_mtu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
