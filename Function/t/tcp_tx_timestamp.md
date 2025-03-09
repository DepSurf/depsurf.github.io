# Function: <code>tcp_tx_timestamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586606016,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:432",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586606016,
      "name": "tcp_tx_timestamp.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587064309,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:431",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587049584,
      "name": "tcp_tx_timestamp.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587260936,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:430",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587246080,
      "name": "tcp_tx_timestamp.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587391441,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:446",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587377664,
      "name": "tcp_tx_timestamp.part.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587894080,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:473",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587894080,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588240992,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:472",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588240992,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588434784,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:472",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588434784,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588835264,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:461",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588835264,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589058384,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:461",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589058384,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590021984,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:460",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590021984,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590064144,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:462",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590064144,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589978736,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:469",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589978736,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590747072,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:469",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590747072,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592378608,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:462",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592378608,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594232352,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:466",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594232352,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594626881,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:466",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595429953,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:467",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502670000,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:461",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502670000,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235374276,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:461",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235374276,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296278480,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:461",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296278480,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278808240,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:461",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278808240,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588664768,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:461",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588664768,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588376752,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:461",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376752,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589100944,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:461",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589100944,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```

```json
{
  "name": "tcp_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589140704,
      "name": "tcp_tx_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:461",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589140704,
      "name": "tcp_tx_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void tcp_tx_timestamp(struct sock * sk, u16 tsflags)
```
</details>
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
