# Function: <code>tcp_bpf_send_verdict</code>

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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588770528,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:298",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588770528,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589203456,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:301",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589203456,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 951
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589428784,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:301",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589428784,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590415216,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:310",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590415216,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 988
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590474384,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:314",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590474384,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 988
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590399616,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:212",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590399616,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 969
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591196384,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:278",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591196384,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1142
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592856608,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:276",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592856608,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1226
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:279",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594733984,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1281
    },
    {
      "addr": 18446744071596355219,
      "name": "tcp_bpf_send_verdict.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:367",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595126368,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1286
    },
    {
      "addr": 18446744071596884027,
      "name": "tcp_bpf_send_verdict.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:381",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595943072,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1347
    },
    {
      "addr": 18446744071597808157,
      "name": "tcp_bpf_send_verdict.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503081376,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:301",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503081376,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235764352,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:301",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235764352,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296789488,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:301",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296789488,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1280
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279136436,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:301",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279136436,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 814
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589033152,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:301",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589033152,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588758192,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:301",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588758192,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589470016,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:301",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589470016,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
```

```json
{
  "name": "tcp_bpf_send_verdict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589515984,
      "name": "tcp_bpf_send_verdict",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:301",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589515984,
      "name": "tcp_bpf_send_verdict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
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
int tcp_bpf_send_verdict(struct sock * sk, struct sk_psock * psock, struct sk_msg * msg, int * copied, int flags)
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
