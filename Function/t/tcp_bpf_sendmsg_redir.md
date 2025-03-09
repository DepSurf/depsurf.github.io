# Function: <code>tcp_bpf_sendmsg_redir</code>

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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588769632,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:280",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588769632,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 889
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589202592,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:283",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589202592,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 863
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589427920,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:283",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589427920,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 863
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590414928,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:210",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590414928,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590474080,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:214",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590474080,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590399312,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:134",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590399312,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591196080,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:134",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591196080,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592856272,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:134",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592856272,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int tcp_bpf_sendmsg_redir(struct sock * sk, bool ingress, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594733648,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:138",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594733648,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int tcp_bpf_sendmsg_redir(struct sock * sk, bool ingress, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595126032,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:161",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595126032,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int tcp_bpf_sendmsg_redir(struct sock * sk, bool ingress, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595942736,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:161",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595942736,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503080584,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:283",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503080584,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235763532,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:283",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235763532,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296788304,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:283",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296788304,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1180
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279135796,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:283",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279135796,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589032288,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:283",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589032288,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 863
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588757328,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:283",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588757328,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 863
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589469152,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:283",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589469152,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 863
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
```

```json
{
  "name": "tcp_bpf_sendmsg_redir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589515104,
      "name": "tcp_bpf_sendmsg_redir",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:283",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict",
        "net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589515104,
      "name": "tcp_bpf_sendmsg_redir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 871
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
int tcp_bpf_sendmsg_redir(struct sock * sk, struct sk_msg * msg, u32 bytes, int flags)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool ingress</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, msg, bytes, flags</code> ➡️ <code>sk, ingress, msg, bytes, flags</code>
</li>
</ul>
</details>
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
