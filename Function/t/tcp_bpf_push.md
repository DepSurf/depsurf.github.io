# Function: <code>tcp_bpf_push</code>

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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588767872,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:212",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588767872,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589200880,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:215",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589200880,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589426208,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:215",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589426208,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590413312,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:142",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590413312,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590472032,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:146",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590472032,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590397568,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:66",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590397568,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591193040,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:66",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591193040,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592853856,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:66",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592853856,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 769
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594730208,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:70",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594730208,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595122288,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:88",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595122288,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1102
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595938896,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:88",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595938896,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1099
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503080040,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:215",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503080040,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235762672,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:215",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235762672,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296784848,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:215",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296784848,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279135034,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:215",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279135034,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589030576,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:215",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589030576,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588755616,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:215",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588755616,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589467440,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:215",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589467440,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
```

```json
{
  "name": "tcp_bpf_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589513344,
      "name": "tcp_bpf_push",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:215",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589513344,
      "name": "tcp_bpf_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
int tcp_bpf_push(struct sock * sk, struct sk_msg * msg, u32 apply_bytes, int flags, bool uncharge)
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
