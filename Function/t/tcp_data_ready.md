# Function: <code>tcp_data_ready</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588303276,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4669",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588296384,
      "name": "tcp_data_ready",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588492150,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4687",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588485216,
      "name": "tcp_data_ready",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588899946,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4698",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588892512,
      "name": "tcp_data_ready",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589124074,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4749",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589116592,
      "name": "tcp_data_ready",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590088176,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4787",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590088176,
      "name": "tcp_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590134112,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4925",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590134112,
      "name": "tcp_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590048336,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4935",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590048336,
      "name": "tcp_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590821728,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4969",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590821728,
      "name": "tcp_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592456496,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4990",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592456496,
      "name": "tcp_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594310752,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:5003",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594310752,
      "name": "tcp_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594697104,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:5008",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594697104,
      "name": "tcp_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595501680,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:5140",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595501680,
      "name": "tcp_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502739860,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4749",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502732496,
      "name": "tcp_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235443864,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4749",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235436252,
      "name": "tcp_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296364272,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4749",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296354720,
      "name": "tcp_data_ready",
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
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278864684,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4749",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278858326,
      "name": "tcp_data_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588730458,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4749",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588722976,
      "name": "tcp_data_ready",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588442442,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4749",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588434960,
      "name": "tcp_data_ready",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589166634,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4749",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589159152,
      "name": "tcp_data_ready",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_data_ready(struct sock * sk)
```

```json
{
  "name": "tcp_data_ready",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589206627,
      "name": "tcp_data_ready",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4749",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_set_rcvlowat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589199120,
      "name": "tcp_data_ready",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void tcp_data_ready(struct sock * sk)
```
</details>
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
