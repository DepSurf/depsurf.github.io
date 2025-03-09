# Function: <code>tcp_enter_cwr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586625936,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2515",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586625936,
      "name": "tcp_enter_cwr.part.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071586626112,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587091290,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2515",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587069568,
      "name": "tcp_enter_cwr.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071587069744,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587288233,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2569",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587266080,
      "name": "tcp_enter_cwr.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071587266256,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587396304,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2533",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587396304,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587918016,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2478",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587918016,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588290381,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2505",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588268816,
      "name": "tcp_enter_cwr.part.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071588268992,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588478984,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2496",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588457600,
      "name": "tcp_enter_cwr.part.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071588457776,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588885991,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2516",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588863824,
      "name": "tcp_enter_cwr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071588864000,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589109970,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2522",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589088032,
      "name": "tcp_enter_cwr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071589088208,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590080332,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2507",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590058672,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590126077,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2610",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590103664,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590039615,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2610",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590017600,
      "name": "tcp_enter_cwr",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590812463,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2644",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590788944,
      "name": "tcp_enter_cwr",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592447197,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2657",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592422624,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594301408,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2668",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594275584,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594687627,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2667",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594661664,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595492476,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2706",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595466144,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502726116,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2522",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502703272,
      "name": "tcp_enter_cwr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446603336502703416,
      "name": "tcp_enter_cwr",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235429884,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2522",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235404932,
      "name": "tcp_enter_cwr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 3235405076,
      "name": "tcp_enter_cwr",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296347064,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2522",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296317888,
      "name": "tcp_enter_cwr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 13835058055296318096,
      "name": "tcp_enter_cwr",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278853140,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2522",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278832688,
      "name": "tcp_enter_cwr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446743936278832818,
      "name": "tcp_enter_cwr",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588716354,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2522",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588694416,
      "name": "tcp_enter_cwr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071588694592,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588428338,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2522",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588406400,
      "name": "tcp_enter_cwr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071588406576,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589152530,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2522",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130592,
      "name": "tcp_enter_cwr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071589130768,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tcp_enter_cwr(struct sock * sk)
```

```json
{
  "name": "tcp_enter_cwr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589192434,
      "name": "tcp_enter_cwr",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:2522",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589170416,
      "name": "tcp_enter_cwr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071589170592,
      "name": "tcp_enter_cwr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
