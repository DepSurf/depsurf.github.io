# Function: <code>sk_msg_trim</code>

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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588179680,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:242",
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
      "addr": 18446744071588179680,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:251",
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
      "addr": 18446744071588507736,
      "name": "sk_msg_trim.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071588505728,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588714576,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:250",
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
      "addr": 18446744071588714576,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589581200,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:251",
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
      "addr": 18446744071589581200,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589590064,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:253",
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
      "addr": 18446744071589590064,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589649664,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:253",
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
      "addr": 18446744071589649664,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590405616,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:253",
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
      "addr": 18446744071590405616,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 957
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592002304,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:262",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592002304,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 775
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593813360,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:262",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593813360,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 787
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594188736,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:263",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594188736,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 787
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594984880,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:263",
      "file": "net/core/skmsg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skmsg.c:sk_msg_alloc",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594984880,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 787
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502275632,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:250",
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
      "addr": 18446603336502275632,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235018864,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:250",
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
      "addr": 3235018864,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295777440,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:250",
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
      "addr": 13835058055295777440,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278511212,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:250",
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
      "addr": 18446743936278511212,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588321312,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:250",
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
      "addr": 18446744071588321312,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588034096,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:250",
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
      "addr": 18446744071588034096,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588653136,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:250",
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
      "addr": 18446744071588653136,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
```

```json
{
  "name": "sk_msg_trim",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588792944,
      "name": "sk_msg_trim",
      "external": true,
      "loc": "net/core/skmsg.c:250",
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
      "addr": 18446744071588792944,
      "name": "sk_msg_trim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void sk_msg_trim(struct sock * sk, struct sk_msg * msg, int len)
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
