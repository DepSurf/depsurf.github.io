# Function: <code>tcp_mtu_to_mss</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586664696,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1318",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666416,
      "name": "tcp_mtu_to_mss",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587118743,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1333",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587112704,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587316834,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1355",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587310944,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587448424,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1434",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587442576,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587969710,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1488",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587963920,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588319525,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1479",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588313360,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588508351,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1467",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588502432,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588920289,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1480",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588912944,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589144065,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589136704,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590114145,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1562",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590107936,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590161739,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1729",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590155264,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590075686,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1729",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590063856,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590849910,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1729",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590837552,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592486004,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1725",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592473600,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594341972,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1722",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594329200,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594729252,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1714",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594714976,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595521321,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1767",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
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
      "addr": 18446744071595511216,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502759920,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502752624,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235464340,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235456880,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296389704,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296380352,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278883126,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278876486,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588750449,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588743088,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588462401,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588455040,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589186625,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589179264,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int tcp_mtu_to_mss(struct sock * sk, int pmtu)
```

```json
{
  "name": "tcp_mtu_to_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589226689,
      "name": "tcp_mtu_to_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_sync_mss",
        "net/ipv4/tcp_output.c:tcp_sync_mss"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589219328,
      "name": "tcp_mtu_to_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
