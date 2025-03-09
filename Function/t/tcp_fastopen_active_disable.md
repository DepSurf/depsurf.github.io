# Function: <code>tcp_fastopen_active_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587501907,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:414",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587501536,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588024179,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:460",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588023824,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588375204,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:453",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588374752,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588565588,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:453",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588565136,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588976760,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:480",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588976320,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589201208,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:480",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589200768,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590173448,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:506",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590173024,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590222696,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:506",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590222240,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590136760,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:506",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590135856,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590916968,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:494",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590915952,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592556904,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:488",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592555808,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594416440,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:489",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594415264,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594805784,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:491",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594804608,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595617016,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:491",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595615808,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502820712,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:480",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502820712,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235522480,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:480",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235522480,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296468496,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:480",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296468496,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278935314,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:480",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278934780,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588807592,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:480",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588807152,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588519528,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:480",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588519088,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589243768,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:480",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589243328,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void tcp_fastopen_active_disable(struct sock * sk)
```

```json
{
  "name": "tcp_fastopen_active_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589284344,
      "name": "tcp_fastopen_active_disable",
      "external": true,
      "loc": "net/ipv4/tcp_fastopen.c:480",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_detect_blackhole",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589283888,
      "name": "tcp_fastopen_active_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void tcp_fastopen_active_disable(struct sock * sk)
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
