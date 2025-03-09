# Function: <code>do_softirq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579390896,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:304",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390896,
      "name": "do_softirq.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071579392896,
      "name": "do_softirq",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579403592,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:304",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403408,
      "name": "do_softirq.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071579404752,
      "name": "do_softirq",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579423064,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:315",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:busy_poll_stop",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579422864,
      "name": "do_softirq.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071579425056,
      "name": "do_softirq",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579410469,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:315",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410304,
      "name": "do_softirq.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071579412816,
      "name": "do_softirq",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579439817,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:316",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579439664,
      "name": "do_softirq.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071579440672,
      "name": "do_softirq",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579454475,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:323",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579454304,
      "name": "do_softirq.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071579455728,
      "name": "do_softirq",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579488802,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:324",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488624,
      "name": "do_softirq.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071579489376,
      "name": "do_softirq",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579506427,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:324",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506272,
      "name": "do_softirq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071579507264,
      "name": "do_softirq",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579532475,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:324",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532320,
      "name": "do_softirq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071579533312,
      "name": "do_softirq",
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
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579563776,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:324",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563776,
      "name": "do_softirq",
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
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579545184,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:233",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "kernel/smp.c:flush_smp_call_function_from_idle",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545184,
      "name": "do_softirq",
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
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579549808,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:447",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "kernel/smp.c:flush_smp_call_function_from_idle",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549808,
      "name": "do_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579621104,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:446",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "kernel/smp.c:flush_smp_call_function_from_idle",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621104,
      "name": "do_softirq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579715789,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:459",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "kernel/smp.c:flush_smp_call_function_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715184,
      "name": "do_softirq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071579715808,
      "name": "do_softirq",
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
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579842557,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:459",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "kernel/smp.c:flush_smp_call_function_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579841888,
      "name": "do_softirq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071579842592,
      "name": "do_softirq",
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
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579892557,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:441",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "kernel/smp.c:flush_smp_call_function_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891264,
      "name": "do_softirq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071579892592,
      "name": "do_softirq",
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
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579930845,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:441",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "kernel/smp.c:flush_smp_call_function_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579929840,
      "name": "do_softirq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071579931264,
      "name": "do_softirq",
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
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490676396,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:324",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490676152,
      "name": "do_softirq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446603336490676416,
      "name": "do_softirq",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224747396,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:324",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224747116,
      "name": "do_softirq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 3224747428,
      "name": "do_softirq",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283498744,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:324",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283498400,
      "name": "do_softirq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 13835058055283499936,
      "name": "do_softirq",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271413184,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:324",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271412944,
      "name": "do_softirq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446743936271413204,
      "name": "do_softirq",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579506139,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:324",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505984,
      "name": "do_softirq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071579506976,
      "name": "do_softirq",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579433963,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:324",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433824,
      "name": "do_softirq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579435744,
      "name": "do_softirq",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579506059,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:324",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505904,
      "name": "do_softirq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071579506896,
      "name": "do_softirq",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void do_softirq()
```

```json
{
  "name": "do_softirq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579538733,
      "name": "do_softirq",
      "external": true,
      "loc": "kernel/softirq.c:324",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__local_bh_enable_ip"
      ],
      "caller_func": [
        "kernel/softirq.c:__local_bh_enable_ip",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538560,
      "name": "do_softirq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071579539648,
      "name": "do_softirq",
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
