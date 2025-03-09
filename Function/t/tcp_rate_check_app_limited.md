# Function: <code>tcp_rate_check_app_limited</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587369296,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:172",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587369296,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587501984,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:173",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587501984,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588024256,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:177",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588024256,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588375312,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:177",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:bpf_tcp_push",
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588375312,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588565696,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:182",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588565696,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588976832,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:183",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588976832,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589201280,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:183",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589201280,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590173520,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:183",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590173520,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590222768,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:183",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590222768,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590136832,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:183",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590136832,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590917040,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:183",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590917040,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592556992,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:194",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592556992,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594416544,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:194",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594416544,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594805888,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:194",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594805888,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595617120,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:194",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595617120,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502821520,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:183",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502821520,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235523104,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:183",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235523104,
      "name": "tcp_rate_check_app_limited",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296469360,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:183",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296469360,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278935436,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:183",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278935436,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588807664,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:183",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588807664,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588519600,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:183",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588519600,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589243840,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:183",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589243840,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void tcp_rate_check_app_limited(struct sock * sk)
```

```json
{
  "name": "tcp_rate_check_app_limited",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589284416,
      "name": "tcp_rate_check_app_limited",
      "external": true,
      "loc": "net/ipv4/tcp_rate.c:183",
      "file": "net/ipv4/tcp_rate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589284416,
      "name": "tcp_rate_check_app_limited",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void tcp_rate_check_app_limited(struct sock * sk)
```
</details>
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
