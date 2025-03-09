# Function: <code>tcp_bpf_recvmsg</code>

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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588773072,
      "name": "tcp_bpf_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:115",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588773072,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 877
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589205952,
      "name": "tcp_bpf_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:118",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589205952,
      "name": "tcp_bpf_recvmsg",
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589431248,
      "name": "tcp_bpf_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:118",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589431248,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 823
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590418688,
      "name": "tcp_bpf_recvmsg",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:264",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590418688,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590477072,
      "name": "tcp_bpf_recvmsg",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:268",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590477072,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590402288,
      "name": "tcp_bpf_recvmsg",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:166",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590402288,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591199872,
      "name": "tcp_bpf_recvmsg",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:237",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591199872,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592859616,
      "name": "tcp_bpf_recvmsg",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:235",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592859616,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594736160,
      "name": "tcp_bpf_recvmsg",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:238",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594736160,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595129776,
      "name": "tcp_bpf_recvmsg",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:323",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595129776,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595946688,
      "name": "tcp_bpf_recvmsg",
      "external": false,
      "loc": "net/ipv4/tcp_bpf.c:331",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595946688,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 583
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503083688,
      "name": "tcp_bpf_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:118",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503083688,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 836
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235767392,
      "name": "tcp_bpf_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:118",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235767392,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 764
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296787168,
      "name": "tcp_bpf_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:118",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296787168,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1124
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279138970,
      "name": "tcp_bpf_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:118",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279138970,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589035616,
      "name": "tcp_bpf_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:118",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589035616,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 823
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588760656,
      "name": "tcp_bpf_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:118",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588760656,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 823
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589472480,
      "name": "tcp_bpf_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:118",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589472480,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 823
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_bpf_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589518480,
      "name": "tcp_bpf_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp_bpf.c:118",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589518480,
      "name": "tcp_bpf_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
int tcp_bpf_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nonblock</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, msg, len, nonblock, flags, addr_len</code> ➡️ <code>sk, msg, len, flags, addr_len</code>
</li>
</ul>
</details>
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
