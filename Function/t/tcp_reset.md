# Function: <code>tcp_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586654224,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3962",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586654224,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587096528,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4020",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587096528,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587294128,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4036",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587294128,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587424912,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3995",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587424912,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587945056,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:3962",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587945056,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588294816,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4043",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588294816,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588483568,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4042",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588483568,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588890848,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4059",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588890848,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589114928,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4109",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589114928,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590085632,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4103",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590085632,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void tcp_reset(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590131184,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4239",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590131184,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void tcp_reset(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590045472,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4246",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590045472,
      "name": "tcp_reset",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_reset(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4280",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592717278,
      "name": "tcp_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590818816,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
void tcp_reset(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4298",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594603654,
      "name": "tcp_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592453424,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void tcp_reset(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4312",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596338970,
      "name": "tcp_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594307680,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void tcp_reset(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4317",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596868370,
      "name": "tcp_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594693920,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void tcp_reset(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4437",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597792571,
      "name": "tcp_reset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595498448,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502730720,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4109",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502730720,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235434412,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4109",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235434412,
      "name": "tcp_reset",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296352368,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4109",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296352368,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278856752,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4109",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278856752,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588721312,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4109",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588721312,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588433296,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4109",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588433296,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589157488,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4109",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589157488,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void tcp_reset(struct sock * sk)
```

```json
{
  "name": "tcp_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589197392,
      "name": "tcp_reset",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4109",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589197392,
      "name": "tcp_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff * skb</code>
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
