# Function: <code>sk_msg_alloc</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588175936,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:25",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588175936,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588501376,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:25",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588501376,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588709696,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:25",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588709696,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589576912,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:26",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589576912,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589586832,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:26",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589586832,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589644688,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:26",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589644688,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590400720,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:26",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590400720,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 706
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592003088,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:26",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592003088,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 878
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:26",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596331846,
      "name": "sk_msg_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593814176,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 860
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:27",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596860661,
      "name": "sk_msg_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071594189552,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 874
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:27",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/xfrm/espintcp.c:espintcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597785761,
      "name": "sk_msg_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071594985696,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 880
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502276056,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:25",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502276056,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235015296,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:25",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235015296,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295771072,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:25",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295771072,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 908
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278507758,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:25",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278507758,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588316432,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:25",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588316432,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588029216,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:25",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588029216,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588648256,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:25",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588648256,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```

```json
{
  "name": "sk_msg_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588787984,
      "name": "sk_msg_alloc",
      "external": true,
      "loc": "net/core/skmsg.c:25",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588787984,
      "name": "sk_msg_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int sk_msg_alloc(struct sock * sk, struct sk_msg * msg, int len, int elem_first_coalesce)
```
</details>
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
