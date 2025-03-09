# Function: <code>tcp_retransmit_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586684704,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:363",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586684704,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1834
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587131696,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:404",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131696,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2074
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587330160,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:409",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587330160,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2192
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587462368,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:405",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587462368,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2246
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587984416,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:413",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587984416,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2234
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588334976,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:405",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588334976,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2332
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588524176,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:431",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588524176,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2594
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588934688,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:427",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588934688,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2702
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589158864,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:431",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589158864,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2718
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590129392,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:437",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590129392,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1667
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590177136,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:448",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590177136,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1661
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590091536,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:448",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590091536,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1556
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:448",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592719834,
      "name": "tcp_retransmit_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071590866752,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1565
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:452",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594606227,
      "name": "tcp_retransmit_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071592503408,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1509
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:446",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596341490,
      "name": "tcp_retransmit_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071594359504,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1511
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:477",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596870781,
      "name": "tcp_retransmit_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071594747472,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1829
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:506",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597794385,
      "name": "tcp_retransmit_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071595553232,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2133
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502775784,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:431",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502775784,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2344
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235479636,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:431",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235479636,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2544
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296410080,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:431",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296410080,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3024
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278896540,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:431",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278896540,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2156
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588765248,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:431",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588765248,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2718
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588477184,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:431",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588477184,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2718
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589201424,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:431",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589201424,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2718
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
void tcp_retransmit_timer(struct sock * sk)
```

```json
{
  "name": "tcp_retransmit_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589241552,
      "name": "tcp_retransmit_timer",
      "external": true,
      "loc": "net/ipv4/tcp_timer.c:431",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589241552,
      "name": "tcp_retransmit_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2721
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
